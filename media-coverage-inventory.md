# Media coverage inventory — phase 1 ledger

Generated **2026-07-31** by `generator/tct/scripts/build_media_coverage.py`.  
Phase: 1 — reconnaissance and coverage ledger (no capture performed)

> **Provenance rule.** A key present with value null/[] means ASSESSED, NOTHING FOUND. A key ABSENT means NEVER ASSESSED. `assessment` records which.

## Headline numbers

| metric | count |
|---|---:|
| tools in registry | 726 |
| **need visual coverage** | **255** |
| …of those, have no media at all today | 211 |
| have any media today | 61 |
| have locally-mirrored media today | 48 |
| blocked (reason recorded) | 64 |

### By population

| population | count |
|---|---:|
| `cli-only-no-visual-needed` | 470 |
| `commercial-crawl` | 184 |
| `self-hostable-web-ui` | 51 |
| `desktop-gui-no-container-route` | 20 |
| `unknown` | 1 |

### How each record was assessed

| assessment | count |
|---|---:|
| `heuristic-tool_type` | 441 |
| `heuristic-registry` | 151 |
| `curated-local-clone` | 77 |
| `curated-fetched-vendor-pages` | 33 |
| `curated-verified-standup` | 24 |

## Self-hostable web UIs — verified stand-up

Ordered lightest-first. Every command and credential is cited to a file path in the read-only clone mirror or a fetched URL.

| tool | category | stand up | URL | credentials | weight | arm64 | blocker |
|---|---|---|---|---|---|---|---|
| caldera | detection-engineering | `git clone https://github.com/mitre/caldera.git --recursive && cd caldera && docker build --build-arg VARIANT=f` | http://localhost:8888 | red / admin (also blue / admin for the blue-team view) when  | light | False | no arm64 image — amd64 emulation required on Apple Silicon |
| dvwa | web-app-security | `git clone https://github.com/digininja/DVWA && cd DVWA && docker compose up -d` | http://localhost:4280 | admin / password | light | True | — |
| juice-shop | web-app-security | `docker pull bkimminich/juice-shop && docker run --rm -p 127.0.0.1:3000:3000 bkimminich/juice-shop` | http://localhost:3000 | No login required to browse; you self-register an account in | light | True | — |
| Velociraptor | dfir | `git clone https://github.com/Velocidex/velociraptor && cd velociraptor/Docker && docker compose up -d` | https://localhost:8889 | admin / password | light | False | no arm64 image — amd64 emulation required on Apple Silicon |
| authentik | identity-access | `mkdir authentik && cd authentik && curl -O https://docs.goauthentik.io/compose.yml && echo "PG_PASS=$(openssl ` | http://localhost:9000/if/flow/initial-setup/ | generated at first boot - the initial-setup flow prompts you | medium | True | — |
| bloodhound | post-exploitation | `curl -O https://raw.githubusercontent.com/SpecterOps/BloodHound/main/examples/docker-compose/docker-compose.ym` | http://localhost:8080/ui/login | admin / generated at first boot - find `# Initial Password S | medium | True | — |
| CISO Assistant | grc | `git clone --single-branch -b main https://github.com/intuitem/ciso-assistant-community.git && cd ciso-assistan` | https://localhost:8443 | generated at first boot - the starter script runs `docker co | medium | True | — |
| Cortex | soar | `git clone https://github.com/TheHive-Project/Cortex && cd Cortex/docker/cortex && job_directory=/tmp/cortex-jo` | http://localhost:9001 | generated at first boot - Cortex serves a 'Update Database'/ | medium | True | — |
| CTFd | endpoint-security | `git clone https://github.com/CTFd/CTFd && cd CTFd && docker compose up` | http://localhost:8000 | generated at first boot - you create the admin account in th | medium | True | — |
| defectdojo | vulnerability-management | `git clone https://github.com/DefectDojo/django-DefectDojo && cd django-DefectDojo && docker compose up -d && d` | http://localhost:8080 | admin / generated at first boot - retrieve with `docker comp | medium | True | — |
| dependency-track | appsec | `curl -O https://raw.githubusercontent.com/DependencyTrack/docs/main/docs/tutorials/docker-compose.quickstart.y` | http://localhost:8081 | admin / admin | medium | True | — |
| Fleet | endpoint-security | `mkdir fleet-deployment && cd fleet-deployment && curl -O https://raw.githubusercontent.com/fleetdm/fleet/refs/` | https://localhost:1337 | generated at first boot - the setup screen walks you through | medium | False | no arm64 image — amd64 emulation required on Apple Silicon; licence/registration gate |
| infisical | secrets-detection | `curl -o docker-compose.prod.yml https://raw.githubusercontent.com/Infisical/infisical/main/docker-compose.prod` | http://localhost:80 | generated at first boot - 'the first user to sign up becomes | medium | True | — |
| Lookyloo | threat-intel | `git clone https://github.com/Lookyloo/lookyloo && cd lookyloo && docker compose up -d` | http://localhost:5100 | No authentication by default; the capture UI is open. Option | medium | build-only | — |
| MISP | threat-intel | `git clone https://github.com/MISP/misp-docker && cd misp-docker && cp template.env .env && docker compose pull` | https://localhost | admin@admin.test / admin | medium | True | — |
| SysReptor | utilities | `curl -s -L --output sysreptor.tar.gz https://github.com/syslifters/sysreptor/releases/latest/download/setup.ta` | http://127.0.0.1:8000 | generated at first boot - you create it with `docker compose | medium | True | licence/registration gate |
| Yeti | threat-intel | `git clone https://github.com/yeti-platform/yeti-docker && cd yeti-docker/prod && /bin/bash ./init.sh && docker` | http://localhost:80 | generated at first boot - no default; create with `docker co | medium | True | — |
| IntelOwl | threat-intel | `git clone https://github.com/intelowlproject/IntelOwl && cd IntelOwl/ && ./initialize.sh && ./start prod up &&` | http://localhost:80 (login at /login) | generated at first boot - create with `docker exec -ti intel | heavy | True | heavy stack (>8GB RAM / 6+ containers) |
| OpenCTI | threat-intel | `git clone https://github.com/OpenCTI-Platform/docker.git && cd docker && cp .env.sample .env && $EDITOR .env  ` | http://localhost:8080 | whatever you set in .env - defaults in .env.sample are admin | heavy | partial | heavy stack (>8GB RAM / 6+ containers) |
| OpenCVE | vulnerability-management | `git clone https://github.com/opencve/opencve.git && cd opencve/docker && ./install.sh prepare && ./install.sh ` | http://localhost:80 (Airflow UI on http://localhost:8080) | generated at first boot - `./install.sh start` runs an inter | heavy | True | heavy stack (>8GB RAM / 6+ containers) |
| Shuffle | soar | `git clone https://github.com/Shuffle/Shuffle && cd Shuffle && docker compose up -d` | http://localhost:3001 (HTTPS on 3443) | generated at first boot - 'Shuffle doesn't have a default us | heavy | partial | heavy stack (>8GB RAM / 6+ containers) |
| TheHive | soar | `git clone https://github.com/StrangeBeeCorp/docker.git && cd docker/prod1-thehive && bash ./scripts/init.sh &&` | http://localhost (port 80; 443 if HTTPS configured) | admin@thehive.local / secret | heavy | True | heavy stack (>8GB RAM / 6+ containers); licence/registration gate |
| Timesketch | dfir | `curl -s -O https://raw.githubusercontent.com/google/timesketch/master/contrib/deploy_timesketch.sh && chmod 75` | http://localhost:80 | generated at first boot - create with `docker compose exec t | heavy | False | no arm64 image — amd64 emulation required on Apple Silicon; heavy stack (>8GB RAM / 6+ containers) |
| Wazuh | siem | `git clone https://github.com/wazuh/wazuh-docker.git -b v4.14.7 && cd wazuh-docker/single-node/ && docker compo` | https://localhost | admin / SecretPassword | heavy | True | heavy stack (>8GB RAM / 6+ containers) |

## Self-hostable web UIs — assessed but no stand-up verified yet

| tool | category | compose in clone | official image | port |
|---|---|---|---|---|
| AI-Infra-Guard | ai-security | docker-compose.yml | zhuquelab/aig-server:latest | 8088 |
| Artemis | vulnerability-management | docker-compose.yaml | certpl/artemis:latest | 5000 |
| Attack Range | detection-engineering | docker/docker-compose.yml | — | 4321 |
| BeEF | exploitation | — | — | 3000 |
| bettercap-ui | network-analysis | — | — | — |
| BunkerWeb | web-app-security | misc/dev/docker-compose.ui.yml | bunkerity/bunkerweb-all-in-one:1.6.13 | 7000 |
| CAPEv2 | malware-analysis | — | — | 8000 |
| CubeSandbox | runtime-security | — | — | 3000 |
| Cyberbro | threat-intel | docker-compose.yml | ghcr.io/stanfrbd/cyberbro:latest | 5000 |
| emisar | ai-infrastructure | docker-compose.yml | ghcr.io/andrewdryga/emisar | 4000 |
| GRR | dfir | compose.yaml | ghcr.io/google/grr:latest | 8000 |
| IntelMQ | threat-intel | — | certat/intelmq-full:latest | 1337 |
| LogonTracer | dfir | docker-compose/docker-compose.yml | jpcertcc/docker-logontracer | 8080 |
| Mythic | exploitation | — | — | 7443 |
| openbao | secrets-detection | — | quay.io/openbao/openbao | 8200 |
| OpenHands | ai-coding-agents | examples/acp-docker/docker-compose.yml | ghcr.io/openhands/agent-canvas:1.7.1 | 8000 |
| redeye | exploitation | docker-compose.yml | ghcr.io/redeye-framework/redeye:latest | 8443 |
| rekono-kbx | exploitation | docker-compose.yml | — | 443 |
| Rspamd | network-defense | — | — | 11334 |
| Runtime Mobile Security | reverse-engineering | — | — | 5491 |
| Security Onion | network-analysis | — | — | 443 |
| starkiller | exploitation | — | — | — |
| teleport | secure-access | — | quay.io/gravitational/teleport | 3080 |
| ThreatMapper | container-security | deployment-scripts/docker-compose.yml | quay.io/deepfenceio/deepfence_ui_ce | 443 |
| Turbinia | dfir | docker/local/docker-compose.yml | us-docker.pkg.dev/osdfir-registry/turbinia/release/turbinia-api-server:latest | 8000 |
| Watcher | threat-intel | docker-compose.yml | ghcr.io/thalesgroup-cert/watcher:latest | 9002 |
| wsgidav | utilities | docker-compose.yml | mar10/wsgidav | 8080 |

## Commercial — verified vendor media pages

| vendor | richness | kind | docs open | gated | best page |
|---|---|---|---|---|---|
| Axonius | high | screenshots | True | False | https://github.com/Axonius/ax-docs-pub |
| Binary Ninja | high | screenshots | True | False | https://docs.binary.ninja/guide/index.html |
| CrowdStrike | high | video | False | False | https://www.crowdstrike.com/en-us/resources/demos/ |
| Cursor | high | both | True | False | https://cursor.com/changelog |
| GitGuardian Detection Engine | high | screenshots | True | False | https://docs.gitguardian.com/releases/saas |
| GitGuardian SaaS | high | screenshots | True | False | https://docs.gitguardian.com/releases/saas |
| GitGuardian Self-Hosted | high | screenshots | True | False | https://docs.gitguardian.com/releases/saas |
| Huntress | high | both | True | False | https://support.huntress.io/api/v2/help_center/en-us/articles.json |
| Microsoft Sentinel | high | screenshots | True | False | https://learn.microsoft.com/en-us/azure/sentinel/investigate-cases |
| Secureframe | high | screenshots | False | False | https://secureframe.com/product-updates |
| Snyk | high | screenshots | True | False | https://github.com/snyk/user-docs |
| Sumo Logic | high | screenshots | True | False | https://github.com/SumoLogic/sumologic-documentation |
| Sysdig Secure | high | screenshots | True | False | https://docs.sysdig.com/en/sysdig-secure/risks/ |
| Tenable | high | screenshots | True | False | https://docs.tenable.com/nessus/Content/Scans.htm |
| Tenable Nessus | high | screenshots | True | False | https://docs.tenable.com/nessus/Content/Scans.htm |
| Tines | high | both | True | False | https://www.tines.com/stories/whats-new/ |
| Twingate | high | screenshots | True | False | https://www.twingate.com/changelog |
| 1Password | medium | screenshots | True | False | https://support.1password.com/create-share-vaults/ |
| Censys | medium | screenshots | True | False | https://docs.censys.com/docs/asm-build-save-automate-queries |
| Drata | medium | screenshots | True | False | https://help.drata.com/en/articles/13265650-quick-start-guide |
| Google SecOps | medium | screenshots | True | False | https://docs.cloud.google.com/chronicle/docs/investigation/udm-search |
| JumpCloud | medium | both | True | False | https://jumpcloud.com/support/get-started-user-interface |
| Varonis | medium | both | False | True | https://www.varonis.com/data-security-platform |
| Burp Suite | low | video | True | False | https://portswigger.net/burp/documentation/desktop/tools/proxy/intercept-messages |
| Exabeam | low | none accessible | False | False | https://docs.exabeam.com/ |
| Okta Identity Engine | low | screenshots | True | False | https://help.okta.com/oie/en-us/content/topics/integrations/aws-radius-intg-user-exp.htm |
| Qualys | low | video | True | False | https://www.qualys.com/apps/vulnerability-management-detection-response/ |
| Rapid7 Insight Platform | low | screenshots | True | False | https://docs.rapid7.com/insightidr/investigations/ |
| Recorded Future | low | none | True | True | https://docs.recordedfuture.com/reference/get-started |
| runZero | low | video | True | False | https://help.runzero.com/docs/release-notes/ |
| Vanta | low | both | True | False | https://help.vanta.com/en/articles/11345397-installing-the-vanta-device-monitor-macos |
| Veracode | low | both | True | False | https://docs.veracode.com/r/EASM_quickstart |
| Wiz | low | screenshots | False | True | https://www.wiz.io/demo |

## Desktop GUI — need a desktop session, not a container

bruteshark, bytecode-viewer, code-oss, detect-it-easy, driftnet, edb-debugger, fern-wifi-cracker, fwbuilder, ghidra, ILSpy, imhex, inspectrum, IPED, jadx, joplin, jsql, OpenSnitch, PCAPdroid, routerkeygenpc, x64dbg

## Not assessed individually

441 tools were bulk-classified `cli-only-no-visual-needed` from their registry `tool_type` alone (`cli`/`library`/`rules`/`other`). They were NOT individually checked for a web UI — a `cli`-typed tool that also ships a dashboard would be missed. That is recorded honestly as `assessment: heuristic-tool_type` rather than presented as a verified negative.

## Licensing — read before capturing any vendor media

Vendor screenshots and demo videos are third-party copyrighted works. Full clause-level findings are in the phase-1 licensing survey. Headline: only **Sumo Logic** (docs repo MIT) and **Microsoft** (docs repos CC BY 4.0 plus an explicit screenshot-permission page) grant reproduction in writing. **Google Cloud docs are CC BY 4.0 for TEXT ONLY** — images are expressly excluded, so the common assumption that Google docs screenshots are freely reusable is wrong. Tenable, CrowdStrike, PortSwigger, Snyk and 1Password carry express anti-framing/anti-mirroring clauses. This is a recommendation for Jon to approve, not a decision taken.

