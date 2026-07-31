# Vendor media on Cyber Toolchain tool pages — licensing / legal landscape

**Prepared:** 2026-07-30 · All pages fetched 2026-07-30 unless noted.
**This is a research summary, not legal advice.** Nothing here is a legal opinion and no
attorney-client relationship exists. Items flagged **[LAWYER]** should get counsel's eyes
before anything ships publicly.

**Reading note on quote fidelity.** Pages were fetched and quoted by an extraction tool.
Where the extraction returned an exact sentence in quotation marks I have reproduced it
verbatim and marked it `VERBATIM`. Where the extraction returned a paraphrase or bullet
summary I have marked it `PARAPHRASE — verify against source before relying on it`.
Anything I could not fetch is marked **NOT READ**, and I make no claim about its contents.

---

## 1. Vendor-by-vendor findings

### Summary table

| Vendor | Website ToU read? | Copying site content | Anti-framing / anti-deep-link | Press/brand kit with explicit editorial grant? |
|---|---|---|---|---|
| Wiz | Yes | Prohibited w/o written consent | Linking OK, no page replication | Media kit exists, **no readable terms** |
| CrowdStrike | Yes | Prohibited w/o written consent | **Deep-linking prohibited** | Brand page 404; **NOT READ** |
| Snyk | Product ToS only | "frame, mirror, republish, download…" prohibited | Framing/mirroring prohibited | Trademark guidelines only, no image grant |
| Tenable | Yes | Prohibited w/o written permission | **Explicit anti-framing clause** | Media kit, **no stated terms** |
| Qualys | Community ToU only | Prohibited w/o written permission | None found in that doc | Media kit, **no stated terms** |
| PortSwigger | Yes | Personal use only; **attribution required** | **No framing; home-page links only** | None found |
| 1Password | Yes | "your own non-commercial use" only | Framing/mirroring prohibited (business terms) | Brand hub exists, **NOT READ** (JS-gated) |
| Okta | Yes | Prohibited w/o separate written agreement | Not found | **YES — explicit content licence** |
| Vanta | **No website ToU exists** on legal center | n/a (only MSA found) | n/a | Press kit via Google Drive, **no stated terms** |
| Microsoft | Yes (Learn ToU) | Restrictive ToU **but** explicit screenshot permission + CC BY 4.0 docs repos | n/a | **YES — best-documented of all 12** |
| Google | Yes (site policies) | Docs text CC BY 4.0; **images explicitly excluded** | n/a | Brand Resource Center; editorial use allowed (paraphrase) |
| Cursor / Anysphere | Yes | **No site-content clause at all** | None | Brand page exists, no usage terms published |

---

### Wiz
**Source:** https://legal.wiz.io/legal (Terms of Use section; www.wiz.io/legal/terms-of-use 308-redirects here). Fetched 2026-07-30.

`VERBATIM` §6.1 Content and Marks:
> "The content on the Website, including without limitation, the text, documents, articles, brochures, descriptions, products, software, graphics, photos, sounds, videos, interactive features, and services (collectively, the 'Content'), and the trademarks, service marks and logos contained therein ('Marks'), are the property of Wiz and/or its licensors"

`VERBATIM` §6.2 Use of Content:
> "Content on the Website is provided to you for your information and personal use only and may not be used, modified, copied, distributed, transmitted, broadcast, displayed, sold, licensed, de-compiled, or otherwise exploited for any other purposes whatsoever without our prior written consent."

`VERBATIM` (retention of notices):
> "If you download or print a copy of the Content you must retain all copyright and other proprietary notices contained therein."

`PARAPHRASE` §8.2 permitted linking — users may link to the Website provided they don't replicate pages, use accurate hyperlink text, don't misrepresent Wiz's endorsement.

**Media kit:** https://www.wiz.io/newsroom — logo pack, headshots, office/team photos, **video B-roll, product images**; last updated 2026-02-26. The only stated condition is `VERBATIM`: *"Our brand is the cornerstone of our identity. Thank you for using it responsibly."* — that is **not** a licence grant. Contact press@wiz.io.

**Net:** mirroring Wiz product images off wiz.io is expressly outside the ToU grant. The media kit is an invitation but grants nothing in writing. Ask press@wiz.io.

---

### CrowdStrike
**Source:** https://www.crowdstrike.com/en-us/legal/website-terms-of-use/. Fetched 2026-07-30. (No "last updated" date surfaced on the page; a search snippet indicated 2026-04-14 — treat that date as unconfirmed.)

`VERBATIM`:
> "The Website in its entirety is owned by CrowdStrike or our licensors and is protected by United States and international laws regarding copyrights, patents, trademarks, trade secrets and other intellectual property or proprietary rights."

`VERBATIM`:
> "You shall not copy, modify, create derivative works of, publicly display or perform, republish, download or store, or transmit any Website content without CrowdStrike's express prior written consent or except as expressly provided in these Terms of Use."

`VERBATIM` (the only licence you get as a visitor):
> "a limited, personal, non-exclusive license to reproduce content as necessary to display the content on a machine that you use to interact with the Website."

`VERBATIM` (linking — note this is unusually aggressive):
> "You may link to our homepage, provided you do so in a way that is fair and legal and does not damage, or take advantage of, our reputation, but you must not establish a link in such a way as to suggest any form of association, approval or endorsement on our part where none exists."

> "You are prohibited from linking to any other page of the Website without our express written permission."

**That last clause purports to prohibit even ordinary deep links to a product page** — which is what the Cyber Toolchain does today on every CrowdStrike tool entry. Such clauses are widely regarded as unenforceable against non-contracting visitors (browsewrap), but it is on the page and it is worth knowing. **[LAWYER]**

**Separate document:** https://www.crowdstrike.com/en-us/legal/terms-conditions/ is the *product* agreement, not website terms. Its §3.3 restriction `VERBATIM` — *"create public Internet 'links' to an Offering or 'frame' or 'mirror' any Offering content on any other server…"* — binds **customers**, not site visitors. Do not conflate the two.

**Brand/press:** https://www.crowdstrike.com/en-us/brand/ returned **404 — NOT READ.** I make no claim about whether CrowdStrike publishes a brand-asset licence.

---

### Snyk
**Source:** https://snyk.io/policies/terms-of-service/. Fetched 2026-07-30.

`VERBATIM` §2 restrictions:
> "copy, modify, duplicate, create derivative works from, frame, mirror, republish, download, display, transmit, or distribute all or any portion of the Services"

`VERBATIM` §5.1:
> "all right, title, and interest in and to the Services, Documentation, and Usage Data, including all Intellectual Property Rights therein, are and will remain, with Snyk and/or its licensors"

**Important caveat:** this document governs *the Services* (the Snyk product), not the marketing website. I did **not** find a separate snyk.io website terms-of-use document. `https://snyk.io/policies/trademark-guidelines/` → **404**.

**Trademark guidelines:** https://dev.snyk.io/policies/snyk-trademark-use-guidelines/ (fetched 2026-07-30 — note this is the `dev.` staging host; the production URL was not located).
`VERBATIM` prohibitions — third parties may not use Snyk trademarks *"in a way that may imply endorsement, sponsorship, or affiliation with third-party products"*, *"as the most prominent element on your web page"*, in company/product/domain names, on merchandise, or in contests.
`VERBATIM` attribution: *"Snyk and the Snyk logo are trademarks owned by Snyk Ltd."* in a *"clear and conspicuous location"*.
`VERBATIM` contact: *"…please contact our legal team at brand@snyk.io"*.
The document **does not** state an affirmative permission for nominative/editorial use — it only lists prohibitions. Extraction explicitly noted: *"The guidelines do not clearly delineate what uses are permitted without permission versus what requires written approval."*

**Press kit:** https://snyk.io/press-kit/ redirects to a contact page with a "Media inquiries" link; **no asset grant published.**

---

### Tenable
**Source:** https://www.tenable.com/legal. Fetched 2026-07-30. (`/legal/terms-of-use` → 404.)

`VERBATIM`:
> "All materials provided on the Site, including but not limited to information, documents, logos, text, graphics, sounds, images, software and all other content of any description available on the Site or included in any products or services we offer (collectively, 'Materials'), are provided either by Tenable or by its respective third party manufacturers, authors, developers and vendors ('Third Party Providers') and are the copyrighted work of Tenable and/or the Third Party Providers."

`VERBATIM`:
> "Except as stated herein, none of the Materials may be copied, reproduced, republished, displayed, or posted in any form or by any means, including but not limited to electronic, mechanical, photocopying, recording or other means, without the prior express written permission of Tenable or the Third Party Providers, as applicable."

`VERBATIM` (anti-framing — the single most on-point anti-hotlink clause in this survey):
> "You may not frame or utilize framing techniques to enclose any trademark, logo, or other proprietary information (including images, text, page layout, or form) of Tenable without Tenable's express written consent."

`VERBATIM`:
> "Elements of the Site are protected by trade dress and other laws and are owned by Tenable, and may not be used, copied or imitated in whole or in part. No logo, graphic, sound or image from the Site may be copied or retransmitted unless expressly permitted by Tenable."

**Media kit:** https://www.tenable.com/media — offers Tenable logos, product logos, fact sheet, executive headshots, brand guidelines. **No product screenshots and no stated usage terms.** Directs press to corporate PR.

---

### Qualys
`https://www.qualys.com/legal/` → **404.** I could not find a general www.qualys.com website terms-of-use document. **NOT READ / does not appear to exist at an obvious URL.**

**Closest available:** https://www.qualys.com/company/community-terms-of-use (Qualys Community). Fetched 2026-07-30.

`VERBATIM`:
> "The Site is provided for your personal use only. Other than content that users submit in accordance with the terms of this Agreement, most of the material on the Site, including graphics, text, design, buttons, logos, images, and icons, as well as the selection, assembly, and arrangement of the Site, is the sole property of the operators of the Site."

`VERBATIM`:
> "Users of the Site may not modify, reproduce, republish, or distribute any material from the Site in any form without the prior written permission of Qualys or the original copyright holder."

Extraction note: *"The terms of use do not contain explicit clauses addressing framing, linking, trademark use, or attribution requirements for third parties."*

**Media kit:** https://www.qualys.com/company/newsroom/media-contacts — logos, logo guidelines, executive headshots, corporate brochure, CISO brochure. **No product screenshots, no stated usage terms.**

---

### PortSwigger (Burp Suite)
**Source:** https://portswigger.net/web-security/certification/terms-and-conditions/website-terms-of-use. Fetched 2026-07-30. (`/terms-and-conditions` → 404; the real ToU lives at the path above, linked from https://portswigger.net/legal.)

`VERBATIM` §7.1:
> "PortSwigger is the owner or the licensee of the Websites, all intellectual property rights in the Websites, and in the material published on it."

`VERBATIM` §7.4:
> "Users may print off one copy, and may download extracts, of any page(s) from the Websites for personal use only and may draw the attention of others within their organisation to content posted on the Websites."

`VERBATIM` §7.5 — **directly on point for screenshots**:
> "Users must not use any illustrations, photographs, video or audio sequences or any graphics separately from any accompanying text."

`VERBATIM` §7.6 — an explicit attribution requirement:
> "PortSwigger's status (and that of any identified contributors) as the authors of content on the Websites must always be acknowledged."

`VERBATIM` §7.7:
> "Users must not use any part of the content on the Websites or share any materials, tools or products obtained from PortSwigger…for any commercial purposes without obtaining a license."

`PARAPHRASE` §13.1–13.5 — links to the home page permitted if fair and legal; the Websites *"must not be framed on any other site, nor may Users create a link to any part of the Websites other than the home page."*

**PortSwigger is a UK company.** UK law has no fair use — only fair dealing (see §2 below). §7.5's ban on using graphics separately from accompanying text is the clearest "no, you may not lift our screenshots" clause in this survey.

**Brand/press:** no brand or media-asset policy found at portswigger.net/legal or /press-releases. **NOT FOUND.**

---

### 1Password (AgileBits)
**Source:** https://1password.com/legal/terms-of-service. Fetched 2026-07-30.

`VERBATIM`:
> "The Service and all contents, including but not limited to text, images, graphics or code are the property of AgileBits Inc. and are protected by copyright, trademarks, database and other intellectual property rights."

`VERBATIM` — the grant, and its limit:
> "You may display and copy, download or print portions of the material from the different areas of the Service only for your own non-commercial use."

> "Any other use is strictly prohibited and may violate copyright, trademark and other laws."

`VERBATIM`:
> "These Terms do not grant you a license to use any trademark of AgileBits Inc. or its affiliates."

`VERBATIM`:
> "You further agree not to use, change or delete any proprietary notices from materials downloaded from the Service."

`VERBATIM` (business customer terms — framing/mirroring):
> "Customer shall not…rent, lease, lend, sell, license, sublicense, publish, frame, mirror or otherwise distribute any part or content."

**Press kit:** https://1password.com/press points to a media kit at https://brand.1password.com/document/45 — `VERBATIM` from the newsroom page: *"Our media kit contains logos, product images, headshots of our leadership team, and brand guidelines."* The brand hub itself is a JS app that returned no readable text — **NOT READ.** No published grant of permission located.

The "your own non-commercial use" phrasing is the one that matters. Whether an ad-free editorial site is "your own non-commercial use" is exactly the ambiguity to resolve. **[LAWYER]**

---

### Okta — the only vendor here with an explicit, readable asset licence
**Source (site ToS):** https://www.okta.com/legal/terms-of-service/. Fetched 2026-07-30.

`VERBATIM`:
> "Except as may otherwise be provided, the Site and the content included in or made available through the Site, such as text, graphics, logos, images, sounds, videos, digital downloads, data compilation, software, and documents, are the exclusive property of Okta"

`VERBATIM`:
> "Scrape, duplicate, reproduce, copy, republish, license, sell, trade or resell the Site or any of its content for any purpose, unless you have specifically been permitted to do so in a separate written agreement"

`VERBATIM`:
> "The Okta graphics, logos, designs, page headers, button icons, scripts, trademarks, and service names are the trademarks or trade dress owned by Okta and may not be used in any manner without the prior written permission of Okta"

**Source (the separate written grant):** https://www.okta.com/terms-of-use-for-okta-content/ — linked from https://www.okta.com/press-room/ with the condition `VERBATIM`: *"By downloading any of these media assets you agree to the Terms of Use for Okta Content."* Newsroom assets: logos & boilerplates (1.7 MB), leadership photos (60 MB), **product images (7.6 MB)**, videos & B-roll.

`VERBATIM` grant:
> "You may use the Okta Content only as it is provided by Okta at https://www.okta.com/newsroom/."

`VERBATIM` restriction:
> "You shall not modify or alter the Okta Content in any way."

`VERBATIM` revocation:
> "Okta may immediately suspend or terminate Your right to use the Okta Content for: (a) Your violation of this Terms of Use, (b) Your violation any terms and conditions governing Your use of Okta's services, or (c) for any other reason that Okta deems appropriate in its sole discretion."

Also prohibited (`PARAPHRASE`): implying Okta sponsorship without written permission; libelous/defamatory/obscene use; disparaging Okta. Attribution is not explicitly required; trademark questions → trademarks@okta.com.

**Practical read:** Okta *does* license its press product images for use as provided, unmodified — which supports mirroring the newsroom asset unchanged (no cropping, no resizing beyond display scaling, no annotation). Two frictions for an editorial site that *rates* products: (a) "disparaging Okta" is a condition, so a critical review could technically void the licence, and (b) it is revocable at will. **[LAWYER]** on the disparagement condition specifically — that is the kind of clause an editorial publisher normally refuses to accept.

---

### Vanta
**Source:** https://www.vanta.com/legal (legal centre index) and https://www.vanta.com/company/press. Fetched 2026-07-30.

**There is no Website Terms of Use / Terms of Use for vanta.com on the legal centre.** Documents listed: Master Subscription Agreement, SLA, Support Policy, Information Security Addendum, MSA FAQ, DPA, EU Data Act Addendum, DORA Addendum, MSP Terms, Privacy Policy, DMCA Notice, Modern Slavery Act Statement. (`/legal/terms-of-use` → 404.)

`PARAPHRASE` (MSA, per search): each party retains its own IP; Vanta may use customer names/logos to identify them as customers.

**Press kit:** https://www.vanta.com/company/press — logos, executive headshots, compliance badges, delivered via a Google Drive link. **No usage terms published on the page.** Contact press@vanta.com.

**Net:** no contractual prohibition was found for vanta.com site content — but absence of a ToU does **not** mean permission. Copyright applies by default with or without a ToU. It only removes the *contract* layer of exposure, not the copyright layer.

---

### Microsoft — the cleanest source in this survey, with a wrinkle
Three separate documents matter, and they say different things.

**(a) Microsoft Learn Terms of Use** — https://learn.microsoft.com/en-us/legal/termsofuse (page metadata: `ms.date` 2025-05-12, `updated_at` 2025-05-12). This one is *restrictive*:

`VERBATIM` — "Personal and Non-Commercial Use Limitation":
> "Unless otherwise specified, the Services are for your personal and non-commercial use. You may not modify, copy, distribute, transmit, publicly display, perform, reproduce, publish, license, create derivative works from, transfer or sell any information, software, products or services obtained from the Services (except for your own, personal, non-commercial use) without prior written consent from Microsoft."

`VERBATIM` — "Notice Specific to Documents Available on this Website" (note the escape hatch in the first sentence):
> "Certain documentation may be subject to explicit license terms separate from the terms contained here. To the extent the terms conflict, the explicit license terms control. Permission to use Documents (such as white papers, press releases, datasheets and FAQs) from the Services is granted, provided that (1) the below copyright notice appears in all copies and that both the copyright notice and this permission notice appear, (2) use of such Documents from the Services is for informational and non-commercial or personal use only and will not be copied or posted on any network computer or broadcast in any media, and (3) no modifications of any Documents are made."

`VERBATIM` — and the image carve-out:
> "Documents specified above do not include the design or layout of the Microsoft.com website or any other Microsoft owned, operated, licensed or controlled site. Elements of Microsoft websites are protected by trade dress, trademark, unfair competition, and other laws and may not be copied or imitated in whole or in part. No logo, graphic, sound or image from any Microsoft website may be copied or retransmitted unless expressly permitted by Microsoft."

So: taking an image *off the learn.microsoft.com page* is prohibited by the Learn ToU — **unless** an explicit separate licence controls, or Microsoft expressly permits it elsewhere. Both of those are true, as follows.

**(b) The docs source repositories are CC BY 4.0.** Verified by direct clone of `github.com/MicrosoftDocs/azure-docs` (default branch `main`), 2026-07-30:
- `LICENSE` — first line `VERBATIM`: **"Attribution 4.0 International"** — i.e. the full text of Creative Commons Attribution 4.0 International (CC BY 4.0). Applies to repository content, which includes the `media/` image directories where the Azure/Sentinel docs screenshots live.
- `LICENSE-CODE` — `VERBATIM`: **"The MIT License (MIT) / Copyright (c) Microsoft Corporation"** (code samples only).
- `README.md` `VERBATIM`: *"## License / For all licensing information, refer to: - [LICENSE](LICENSE)"*

This is the "explicit license terms [that] control" the Learn ToU points to. **Nuance worth noting: unlike Google, Microsoft's docs licence contains no carve-out excluding images from the CC BY grant.** CC BY 4.0 requires attribution: title, author, source, licence, and an indication if changes were made.

**(c) Microsoft's screenshot permissions policy** — https://www.microsoft.com/en-us/legal/intellectualproperty/permissions (and `/permissions/default`). Fetched 2026-07-30. This is a standing, express permission and it is the strongest grant found anywhere in this survey:

`VERBATIM` permitted use:
> "You may use other screenshots in advertising, in documentation (including educational brochures), in tutorial books, in videos, or on websites"

`VERBATIM` prohibited:
> "You may not use screenshots of Microsoft product boot-up screens, opening screens, 'splash screens,' or screens from beta release products"

`VERBATIM` conditions:
> "Do not alter the screenshot except to resize it"
> "Do not use portions of screenshots"
> "Do not include screenshots in your product user interface"
> "Do not use screenshots that contain third-party content"
> "Do not use screenshots that contain an image of an identifiable individual"

`VERBATIM` required credit:
> "Used with permission from Microsoft."

`PARAPHRASE` — general requirements also apply: use full product names, use plain-text links, avoid offensive use. Extraction noted the screenshots section *"does not specifically mention comparative advertising restrictions."* — I did not read a comparative-use clause, so I make no claim either way.

**(d) Microsoft trademark rules** — https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks. `PARAPHRASE`: wordmarks and product names may be used truthfully and referentially (e.g. news headlines, "works with Microsoft Teams", as adjectives); **logos, icons and designs may not be used without an express licence**; your brand must be less prominent than Microsoft's is not the rule — rather, your brand should appear *more* prominently than Microsoft's; required footnote `VERBATIM`: *"Microsoft, (list trademarks) are trademarks of the Microsoft group of companies."*

**Net for Microsoft:** the cleanest path in the survey. Take the screenshot images from the CC BY 4.0 docs repos (with CC BY attribution), or take Microsoft product screenshots yourself under the express screenshots permission (unaltered except resize, whole screenshots only, credit line "Used with permission from Microsoft"). Do **not** reuse Microsoft *logos*.

---

### Google (Cloud / SecOps docs)
**Source:** https://developers.google.com/terms/site-policies (cloud.google.com/site-policies 301-redirects here). Fetched 2026-07-30.

`VERBATIM`:
> "the content of this page is licensed under the Creative Commons Attribution 4.0 License"
> "code samples are licensed under the Apache 2.0 License"

`VERBATIM` exclusions — **this is the critical finding**:
> "Google's trademarks and other brand features are not included in this license"
> "a page may include content consisting of images, audio or video material, or a link to content on a different webpage…This content is not covered by the license, unless specifically noted"

`VERBATIM` attribution, exact reproduction:
> "Portions of this page are reproduced from work created and shared by Google and used according to terms described in the Creative Commons 4.0 Attribution License"

`VERBATIM` attribution, modified:
> "Portions of this page are modifications based on work created and shared by Google"

Both require linking back to the original source page.

**Confirmed live on a Google Cloud security docs page** — https://docs.cloud.google.com/security-command-center/docs/security-command-center-overview (Last updated 2026-07-27 UTC), footer `VERBATIM`:
> "Except as otherwise noted, the content of this page is licensed under the Creative Commons Attribution 4.0 License, and code samples are licensed under the Apache 2.0 License."

> **⚠️ The widespread assumption that "Google Cloud docs are CC BY so the screenshots are too" is wrong.** The licence text expressly excludes images unless specifically noted. **Google Cloud docs screenshots are NOT CC BY.** This is the opposite of the Microsoft position and the single most important correction in this report.

**Google brand permissions** — https://about.google/brand-resource-center/ 301-redirects to https://partnermarketinghub.withgoogle.com/brands/google/overview/; the brand-elements page redirects to `.../branding-guidelines/how-to-show-googles-brand/`. Fetched 2026-07-30. All of the following is `PARAPHRASE — verify against source before relying on it`:
- Logos: permitted for "educational and informational uses (news articles, classroom materials)"; `VERBATIM` prohibition: *"Don't use the Google logo in marketing materials for a business or to imply endorsement from Google"*.
- Product visuals (screenshots/UI): permitted for educational and informational/news contexts; permission required for compatibility demonstrations and entertainment; `VERBATIM` prohibitions: *"Don't recreate or modify Google's product UI"*, *"Don't use Google Doodles in any way"*.
- Product icons: require a Partner Marketing Hub account and approval; `VERBATIM`: *"Make sure your brand is more prominent than Google's product icon"*.
- `VERBATIM`: *"Don't use Google's brand colors in your work"*, *"Don't use or mimic Google's brand font in your work"*.

**Google ToS** — https://policies.google.com/terms, `VERBATIM`: *"You may use Google's content as allowed by these terms and any service-specific additional terms, but we retain any intellectual property rights that we have in our content."* and *"Don't remove, obscure, or alter any of our branding, logos, or legal notices. If you want to use our branding or logos, please see the Google Brand Permissions page."*

**Net for Google:** docs *text* is reusable under CC BY 4.0 with the prescribed attribution paragraph. Docs *images/screenshots* are not. The brand centre appears to permit editorial/news use of product visuals, but I only have a paraphrase of that, so it should be re-read directly before relying on it. **[LAWYER]**

---

### Cursor / Anysphere
**Source:** https://cursor.com/terms-of-service. Fetched 2026-07-30.

Extraction finding, quoted: *"there are no specific clauses addressing copyright in website content, permissions/prohibitions on copying, downloading, distributing content or images, framing, hotlinking, linking practices, trademark use, or attribution requirements."* The document contains §5.1 IP ownership (`VERBATIM`: *"Anysphere and its licensors shall own and retain all right, title and interest in and to the Service"*), §11 copyright complaints, and §13 indemnity — none of which address site content reuse.

**Brand page:** https://cursor.com/brand. Only two usable statements, both `VERBATIM`: *"Resources to represent Cursor consistently and accurately."* and *"Refer to us as Cursor. Not Cursor AI or Cursor Code."* No usage grant, no restrictions, no attribution requirement published on the page. Detailed terms, if any, are inside the downloadable asset package — **NOT READ.**

**Net:** no contractual restriction found; also no permission found. Copyright default applies.

---

### YouTube — embedding
**Source:** https://www.youtube.com/t/terms. Fetched 2026-07-30.

`VERBATIM` — "Permissions and Restrictions":
> "You may view or listen to Content for your personal, non-commercial use. You may also show YouTube videos through the embeddable YouTube player."

`VERBATIM` — "License to Other Users" (this is the clause that actually makes third-party embedding lawful):
> "You also grant each other user of the Service a worldwide, non-exclusive, royalty-free license to access your Content through the Service, and to use that Content, including to reproduce, distribute, prepare derivative works, display, and perform it, only as enabled by a feature of the Service (such as video playback or embeds)."

`VERBATIM` — "License to YouTube":
> "By providing Content to the Service, you grant to YouTube a worldwide, non-exclusive, royalty-free, sublicensable and transferable license to use that Content (including to reproduce, distribute, prepare derivative works, display and perform it) in connection with the Service and YouTube's (and its successors' and Affiliates') business, including for the purpose of promoting and redistributing part or all of the Service."

`PARAPHRASE` — restrictions list: users may not access, reproduce, download, distribute, transmit, broadcast, display, sell, license, alter or modify the Service except as expressly authorized; may not circumvent security; may not use bots/scrapers without permission; may not view/listen to content for commercial purposes; may not sell advertising on pages where YouTube content is the primary draw.

**Reading:** every uploader — including a vendor uploading its own demo video — grants every other user a licence to use that content *as enabled by a feature of the Service, expressly including embeds*. Embedding a vendor's own YouTube video via the standard iframe is therefore **licensed by contract**, not merely tolerated. Two caveats worth carrying: (1) the "may not sell advertising on pages where YouTube content is the primary draw" restriction constrains future monetisation of a page built around embeds; (2) uploaders can restrict embedding, delete, or privatise videos at any time — link rot is real. Downloading the mp4 and self-hosting it is expressly prohibited.

---

## 2. The legal doctrines, accurately

### 2.1 Copyright in a product UI screenshot
- A screenshot of a product UI is a **reproduction of the vendor's copyrighted work**. The vendor (or its licensors) holds copyright in the underlying screen elements: icons, illustrations, photographs, chart renderings, marketing copy, and the selection/arrangement of the interface.
- **You get no new copyright by pressing the shutter.** A screenshot is generally not an original work of authorship of the person capturing it (*Feist Publications v. Rural Telephone*, 499 U.S. 340 (1991) — originality requires a minimal spark of creativity). So "I took it myself" changes the *contract* and *provenance* story, not the *copyright* story.
- **Not everything on screen is protectable.** Functional layout, standard UI conventions, and unadorned data are thin or unprotectable. *Lotus Development v. Borland*, 49 F.3d 807 (1st Cir. 1995) (menu command hierarchy = uncopyrightable "method of operation"); *Apple Computer v. Microsoft*, 35 F.3d 1435 (9th Cir. 1994) (individual GUI elements largely unprotectable; only "virtual identity" of the overall look infringes). In *Google v. Oracle*, 593 U.S. 1 (2021), the Supreme Court assumed copyrightability and decided on fair use — deliberately leaving the protectability question open.
- Practical effect: a screenshot of a dashboard full of graphs and generic controls sits at the thin end of the protection spectrum. A screenshot dominated by a vendor's illustration, logo, or marketing artwork sits at the thick end.

### 2.2 US fair use for editorial / commentary / comparative use
17 U.S.C. §107. All four factors, weighed together, fact-specific, **and essentially never predictable in advance — there is no safe harbour and no bright line.** Every statement below is a tendency, not a rule.

1. **Purpose and character.** Criticism, comment, news reporting, and scholarship are the statute's named favoured purposes, and a site that profiles and rates tools is squarely in that territory. Post-*Andy Warhol Foundation v. Goldsmith*, 598 U.S. 508 (2023), "transformative" is narrower than it used to be: the question is whether the *use* has a genuinely different purpose from the original, and commercial character weighs against. A screenshot used to *illustrate and support commentary about the product* has a different purpose than the vendor's own promotional use of the same image. A screenshot used decoratively — to make a page look nicer — does not, and that distinction is the whole ballgame.
   - **"Non-commercial-ish" is the weak point.** In fair-use analysis "commercial" is broader than "makes money." If the site ever carries ads, sponsorships, affiliate links, or serves as lead-gen, factor 1 shifts. Right now it is ad-free editorial, which is about as good as it gets.
2. **Nature of the work.** Product UI is largely factual/functional rather than highly expressive — this factor generally favours the user. It is also already published, which favours the user.
3. **Amount and substantiality.** A single screenshot is a small portion of the *product* but 100% of the *image*. Courts have repeatedly accepted whole-image reproduction where the use requires it and the reproduction is scaled to purpose: *Bill Graham Archives v. Dorling Kindersley*, 448 F.3d 605 (2d Cir. 2006) (concert posters reproduced whole, reduced in size, in a biography — fair use); *Kelly v. Arriba Soft*, 336 F.3d 811 (9th Cir. 2003) and *Perfect 10 v. Amazon.com*, 508 F.3d 1146 (9th Cir. 2007) (thumbnails — fair use). Practical takeaway: **use the smallest image that does the editorial job**, and don't reproduce more of the vendor's marketing artwork than the commentary needs.
4. **Market effect.** A tool-review screenshot does not substitute for buying the product, which is the vendor's actual market. The residual risk is the *licensing market for the image itself* — and vendors that run a paid image-licensing business are rare in B2B security. This factor generally favours editorial use here.

**Bottom line, honestly stated:** editorial use of a product screenshot alongside genuine commentary is the paradigm case people cite as fair use, and I am not aware of a US case where a software vendor successfully sued a reviewer over a product screenshot. But **fair use is an affirmative defence you raise after being sued**, not a permission you hold in advance, and its application here is untested per-vendor and per-image. The cost of being wrong is usually a takedown demand, not damages — but it is a demand you have to answer.

### 2.3 Trademark and brand guidelines — a separate axis
- Copyright and trademark are **independent**. A CC BY licence on documentation does not license the logos in it — Google says so explicitly, and Microsoft's trademark rules say logos need a separate licence.
- **Nominative fair use** protects referring to a product by its name in order to talk about it: *New Kids on the Block v. News America Publishing*, 971 F.2d 302 (9th Cir. 1992), refined in *Toyota Motor Sales v. Tabari*, 610 F.3d 1171 (9th Cir. 2010). Three-part test: (i) the product isn't readily identifiable without the mark, (ii) only so much of the mark is used as is reasonably necessary, (iii) nothing suggests sponsorship or endorsement. Naming "Wiz" and "CrowdStrike Falcon" on a tool page is core nominative use.
- **Logos strain prong (ii).** Using the wordmark is "only so much as necessary"; using the stylised logo often isn't. Several vendors here say so directly (Okta, 1Password, Microsoft, Snyk).
- **The real trademark risk for a rating site is implied endorsement**, not infringement of the mark itself. Grids of vendor logos on a site that scores products can read as "these vendors participate." Mitigate with a visible, unambiguous disclaimer: no affiliation, no endorsement, all marks belong to their owners, independent editorial.
- **Brand guidelines are not law.** They are the vendor's licensing terms plus a statement of what will annoy them. Violating them is not automatically infringement — but it removes your "we followed their published rules" defence and makes a demand letter more likely.
- **Right of publicity / privacy**: screenshots containing identifiable individuals (demo data with real names, headshots in a user list) carry a separate claim. Microsoft calls this out explicitly. Redact or avoid.

### 2.4 Hotlinking vs mirroring — legal exposure
**They fail differently, and hotlinking is *not* the safe option.**

**Mirroring** is an unambiguous act of reproduction and public display. It needs either a licence (Microsoft screenshots policy, CC BY docs, Okta content terms) or fair use. It is a clean, single legal question. It is also **remediable**: a takedown demand is satisfied by deleting a file.

**Hotlinking** avoids making a copy on your server, and in the Ninth Circuit that matters a great deal:
- *Perfect 10 v. Amazon.com*, 508 F.3d 1146 (9th Cir. 2007) established the **"server test"**: a site that inline-links an image without storing it does not "display" a copy and so does not directly infringe the display right. Reaffirmed in *Hunley v. Instagram*, 73 F.4th 1060 (9th Cir. 2023).
- **The Second Circuit has gone the other way.** *Goldman v. Breitbart News Network*, 302 F. Supp. 3d 585 (S.D.N.Y. 2018) rejected the server test; followed by *Nicklen v. Sinclair Broadcast Group*, 551 F. Supp. 3d 188 (S.D.N.Y. 2021) and *McGucken v. Newsweek*, 464 F. Supp. 3d 594 (S.D.N.Y. 2020). Embedding in New York can be a display, and therefore direct infringement.
- So the copyright answer to "is hotlinking safe?" is **"it depends which circuit sues you in,"** which is a worse answer than the mirroring question has.
- Separately, hotlinking **squarely violates the express anti-framing / anti-deep-linking clauses** quoted above from Tenable, CrowdStrike, PortSwigger, Snyk, 1Password and (partially) Wiz. Even where a copyright claim would fail, a breach-of-terms theory is available. Browsewrap terms are hard to enforce against a non-registering visitor (*Nguyen v. Barnes & Noble*, 763 F.3d 1171 (9th Cir. 2014)), but "hard to enforce" is not "no letter arrives."
- **[LAWYER]** the circuit-split point if hotlinking is seriously considered.

### 2.5 Non-legal risks of hotlinking (these are the decisive ones)
1. **Link rot.** Vendors reorganise marketing sites constantly. A hotlinked screenshot becomes a broken image with no warning and no build-time signal. Across ~726 tools this is a permanent, growing maintenance tax.
2. **Referer blocking / hotlink protection.** Most vendor CDNs (Cloudflare, Akamai, Fastly) offer one-click hotlink protection keyed on `Referer`. The day a vendor enables it, your images 403 — for everyone, silently.
3. **Silent content swap.** The vendor controls the bytes at that URL forever. They can replace a product screenshot with a rebranded one, a "please stop hotlinking" placeholder, an ad, or something worse. Your page renders whatever they serve, under your byline, with no review. **This is the single strongest argument against hotlinking** for a site whose value proposition is editorial trustworthiness.
4. **Visitor IP leakage.** Every reader's IP address, User-Agent, and `Referer` (revealing the exact Cyber Toolchain page they're reading) goes to the vendor's server on every page load, along with any cookies that host has set. That is a third-party data flow you'd be creating on your readers' behalf without disclosure. It is a privacy-notice obligation under GDPR/UK GDPR for EU/UK readers, and it hands ~726 security vendors a live analytics feed showing who reads their competitors' pages on your site. For a site that profiles vendors, that is also a conflict-of-interest smell.
5. **Performance and integrity.** No control over image size, format, caching, or availability; no subresource integrity for images; potential mixed-content and CSP complications; page speed hostage to the slowest vendor CDN.
6. **You cannot honour a takedown you don't control** — and equally, you cannot preserve an archival record of what a product looked like in 2026, which is precisely the longitudinal signal `trends/` exists to capture.

### 2.6 One risk specific to mirroring on GitHub Pages
Mirrored assets land in a **public git repository with permanent history**. Honouring a takedown means not just deleting the file but rewriting published history across two repos (`generator/site/public/tool-media/` and the built `cybertoolchain.github.io` repo) — expensive, and something already learned the hard way once in this workspace. Also: repeated DMCA notices against a GitHub account trigger GitHub's repeat-infringer policy. If mirroring goes ahead, **keep mirrored media out of git history** — e.g. an S3/R2 bucket fetched at build time, or at minimum a separate, squashable repo — so a takedown is a delete, not a history rewrite. **[LAWYER]** not required for this one; it's an architecture call.

### 2.7 Non-US law — the site is globally readable
There is **no fair use outside the US**. The UK (PortSwigger, Snyk Ltd) and the EU have narrow, enumerated exceptions instead:
- UK CDPA 1988 **s.30(1)** — fair dealing for criticism or review, and **s.30(2)** for reporting current events — both require **"sufficient acknowledgement"** (title and author) and that the work has been made available to the public. A tool-profile page with commentary plausibly fits criticism/review; a decorative screenshot does not.
- EU: InfoSoc Directive Art. 5(3)(d) quotation exception for criticism/review, transposed unevenly; the "quotation" framing for images is much weaker than for text in most member states.
Practical effect: the **acknowledgement/attribution requirement is not optional** if UK/EU vendors are in scope, and PortSwigger's §7.6 says so directly. Whatever media policy is adopted should credit source + vendor + link on every asset. That single habit satisfies CC BY, satisfies UK sufficient acknowledgement, and satisfies most brand guidelines at once.

---

## 3. Low-risk alternatives, and how good each actually is

| Alternative | How good | Detail |
|---|---|---|
| **Vendor YouTube embeds** | **Excellent — best legal footing available** | YouTube ToS grants every user a licence to use uploaded content "only as enabled by a feature of the Service (such as video playback or embeds)". This is an express contractual grant from the uploader, not a fair-use gamble. Use `youtube-nocookie.com` and lazy-load facades to limit visitor tracking. Limits: only helps where the vendor has a YouTube demo; uploader can disable embedding or delete; embeds still leak visitor data to Google (disclose it); YouTube restricts selling ads on pages where their content is the primary draw. |
| **Microsoft: CC BY 4.0 docs images + express screenshots policy** | **Excellent** | Two independent grants stack. Docs repo images are CC BY 4.0 with no image carve-out; separately, Microsoft expressly permits screenshots "on websites" with the credit "Used with permission from Microsoft." Conditions are easy to meet: don't crop, don't use splash/boot screens, no identifiable people, no third-party content in frame. |
| **Okta press content licence** | **Good, with a catch** | The only vendor here that ships a written licence with its product images. But it's "as provided," unmodified, revocable at will, and conditioned on not disparaging Okta — awkward for a site that rates products. |
| **Self-captured screenshots** | **Very good editorially; still copyright-dependent** | Removes the "you scraped our website" contract problem entirely, gives clean provenance, and lets you show the *same* view across competing tools — which is exactly what makes a comparison page valuable. But it does **not** create a copyright you own; the underlying UI is still the vendor's, and you still lean on fair use. Practical ceiling: only works for open-source, self-hostable, free-tier, or demo-accessible products — which is most of the OSS half of the 726 but few of the enterprise SaaS half. Avoid capturing any demo data containing real names/emails. |
| **Link out only** | **Zero legal exposure; weakest editorially** | A "See the product →" link is unimpeachable (modulo CrowdStrike's odd deep-link clause). Costs the visual density that makes tool pages useful. Best used as the universal fallback rather than the primary design. |
| **Other vendor press kits (Wiz, Tenable, Qualys, Vanta, 1Password, Snyk, CrowdStrike, PortSwigger, Cursor)** | **Weak — invitation without a grant** | Every one of these either publishes no usage terms, or publishes trademark prohibitions only. A press kit's existence is evidence of intent to have assets used, and helps the equities, but it is not a licence. The fix is cheap: **email press@ / brand@ and ask for written permission.** A one-paragraph email to twelve press addresses converts most of this survey's uncertainty into written grants, and vendors almost always say yes to an editorial site that will show their product. |
| **Vendor-authored descriptive text under CC BY** | Bonus | Google Cloud docs *text* is CC BY 4.0 (images are not). Microsoft docs text and images are both CC BY 4.0. Useful for factual product descriptions if that's ever wanted, with the prescribed attribution paragraph. |

---

## 4. Recommendation matrix

Scores: ⬤⬤⬤ = high / worst, ⬤ = low / best. "Legal exposure" and "operational risk" are risks (lower is better); "editorial quality" is a benefit (higher is better).

| Option | Legal exposure | Operational risk | Effort | Editorial quality |
|---|---|---|---|---|
| **Mirror vendor screenshots** (no written grant) | ⬤⬤ Medium. Clear reproduction; relies on fair use. Contradicts express ToU at Wiz, CrowdStrike, Tenable, Qualys, PortSwigger, 1Password, Okta. Remediable by deletion. No fair use for UK/EU vendors. | ⬤ Low. Stable, fast, self-contained, archivable. Main issue: takedown means git-history rewrite unless assets are kept out of git. | ⬤⬤ Medium. Content-addressed store, provenance metadata, refresh job, takedown process. | ⬤⬤⬤ High. Full control of crop, size, format, consistency across 726 pages. |
| **Mirror *with* a written grant** (Microsoft CC BY + screenshots policy; Okta content terms; any vendor that replies yes to an email) | ⬤ Low. Licensed, not defended. | ⬤ Low. Same as above. Okta's grant is revocable; Microsoft's is a standing published policy. | ⬤⬤ Medium, plus per-vendor licence tracking and a one-time outreach email round. | ⬤⬤⬤ High. |
| **Hotlink vendor screenshots** | ⬤⬤ Medium-and-unpredictable. Ninth Circuit server test says no display (*Perfect 10*, *Hunley*); Second Circuit says it can be (*Goldman*, *Nicklen*, *McGucken*). Plus direct breach of express anti-framing/deep-link clauses at Tenable, CrowdStrike, PortSwigger, Snyk, 1Password. | ⬤⬤⬤ **High — disqualifying.** Link rot at scale, referer-blocking 403s, silent content swap under your byline, ~726 vendors receiving every reader's IP + the page they're reading. | ⬤ Lowest to build, highest to maintain forever. | ⬤⬤ Medium and unstable — you don't control size, format, or whether it renders at all. |
| **Embed vendor YouTube videos** | ⬤ **Lowest of any option that shows media.** Express licence in YouTube ToS from uploader to every other user, explicitly covering embeds. | ⬤ Low-medium. Uploader can delete/privatise/disable embedding; visitor data goes to Google (disclose); needs a facade/lazy-load to avoid a heavy third-party payload. | ⬤ Low. Standard iframe + a nocookie facade component. | ⬤⬤⬤ High where a demo video exists — motion beats a still. But coverage is patchy across 726 tools. |
| **Link out only** | ⬤ **None.** (One curiosity: CrowdStrike's ToU purports to bar non-homepage links; broadly regarded as unenforceable against visitors.) | ⬤ Minimal — links rot but degrade gracefully. | ⬤ Trivial; largely already done. | ⬤ Low. No visual signal on the page. |
| **Self-captured screenshots** | ⬤ Low-medium. No contract/scraping issue; still the vendor's UI copyright, so still fair use — but the *strongest* fair-use posture, because the use is unambiguously your own editorial act. | ⬤ Low. You own the file and the pipeline. Capture must be re-run as UIs change. | ⬤⬤⬤ **Highest.** Needs a capture harness, account/demo access, and periodic re-capture. Only feasible for OSS/self-hostable/free-tier/demo products. | ⬤⬤⬤ **Highest.** Consistent framing across tools is the thing no vendor asset can give you, and it's the actual differentiator for a comparison site. |

---

## 5. What I'd recommend, and why

**Recommended posture: a four-tier ladder, evaluated per tool, with hotlinking excluded entirely.**

1. **Embed the vendor's own YouTube demo** where one exists. This is the only option with an express written licence covering exactly what you'd be doing, granted by the uploader to every other YouTube user, in YouTube's own terms. Use `youtube-nocookie.com` behind a click-to-load facade so no third-party request fires until a reader asks for it.
2. **Self-capture** for everything self-hostable, open-source, free-tier, or demo-accessible. This is the highest-effort tier and the highest-value one: consistent framing across competing tools is editorial value that no vendor press kit can supply, and it converts the legal question from "we copied their file" into "we photographed their product to review it," which is the strongest fair-use posture available. Given the tool mix, this likely covers the OSS majority of the 726.
3. **Mirror only where there is a written grant.** Today that means Microsoft (CC BY 4.0 docs images *plus* the standing screenshots policy — the cleanest source in the survey) and Okta (press content terms, unmodified, subject to a disparagement condition worth reviewing). **Then go get more grants:** one short email to the twelve press@/brand@ addresses turns most of this report's grey area into written permission, and vendors overwhelmingly want their product shown on a site profiling their category. That email round is the highest-leverage hour in this whole plan.
4. **Link out** as the universal fallback. No media beats risky media on a site whose asset is editorial credibility.

**Why not hotlink, in one line:** it is worse than mirroring on every axis that matters and better on only one contested, jurisdiction-dependent copyright point — while directly violating express anti-framing clauses at Tenable, CrowdStrike, PortSwigger, Snyk and 1Password, and handing ~726 security vendors a live feed of your readers' IP addresses and which competitor's page they're reading. The silent-content-swap risk alone should end the discussion: a vendor can replace the bytes at that URL at any time, and whatever they serve renders on your page under your name.

**Why not blanket-mirror either:** the fair-use case for editorial screenshots is genuinely strong in the US, and I'd expect any dispute to arrive as a takedown email rather than a lawsuit — but it is a defence, not a permission, and it evaporates for UK and EU vendors, who get fair dealing with a mandatory acknowledgement requirement instead. Mirroring without grants converts an unforced-error-free position into a standing obligation to answer letters.

**Three things to build in regardless of which mechanic is approved:**
- **Per-asset provenance metadata** — source URL, capture/fetch date, licence basis (`cc-by-4.0` / `ms-screenshot-policy` / `okta-content-tou` / `self-captured` / `fair-use-editorial`), and required attribution string. Content-addressing gives you dedupe; the licence field gives you a takedown story and makes a bulk audit a query instead of a project.
- **Attribution on every asset** — source, vendor, licence, link. This one habit simultaneously satisfies CC BY 4.0, UK CDPA s.30 "sufficient acknowledgement", Microsoft's "Used with permission from Microsoft", and most brand guidelines.
- **A visible non-affiliation disclaimer** and a documented, findable takedown contact. Both materially reduce the chance a vendor's first move is a lawyer rather than an email.

---

## 6. Flag for a lawyer before shipping publicly

1. **Is the site "commercial"?** Several grants turn on it — 1Password's "your own non-commercial use", Microsoft Learn's "personal and non-commercial use", PortSwigger's "commercial purposes without obtaining a license" — and fair-use factor 1 uses a broader definition of commercial than "makes money." Get a view now, and re-check it the day ads, sponsorship, affiliate links, or a paid tier are considered.
2. **Okta's disparagement condition.** The Okta Content licence is conditioned on not disparaging Okta and is revocable at Okta's sole discretion. That is a condition an editorial publisher would normally decline. Decide whether to accept it or to rely on fair use for Okta instead.
3. **Trademark / implied endorsement across a ratings site.** Logo grids plus scores is the fact pattern where nominative fair use gets tested. Have counsel bless the disclaimer wording and the logo-usage rules (wordmark vs stylised logo).
4. **UK/EU exposure.** No fair use for PortSwigger, Snyk Ltd, Wiz, or any EU vendor. Confirm the criticism/review fair-dealing framing and the sufficient-acknowledgement format.
5. **CrowdStrike's no-deep-linking clause** — almost certainly unenforceable against a visitor, but it's currently being contradicted by every CrowdStrike link on the site. Worth a two-minute sanity check.
6. **Re-read the Google Brand Resource Center directly.** My finding that Google permits editorial/informational use of product visuals is a **paraphrase** from a redirected partner-marketing site, not a verbatim quote. Do not rely on it as read.
7. **Confirm the Microsoft stack.** The argument is that the docs-repo CC BY 4.0 licence is an "explicit license term" that controls over the restrictive Learn ToU (which the Learn ToU itself invites), *and* that the standing screenshots policy independently permits website use. Both look solid; both are worth a professional read since Microsoft would be the largest single source of mirrored media.

## 7. Sources fetched (all 2026-07-30)

- https://legal.wiz.io/legal · https://www.wiz.io/newsroom
- https://www.crowdstrike.com/en-us/legal/website-terms-of-use/ · https://www.crowdstrike.com/en-us/legal/terms-conditions/ · https://www.crowdstrike.com/en-us/brand/ **(404)**
- https://snyk.io/policies/terms-of-service/ · https://dev.snyk.io/policies/snyk-trademark-use-guidelines/ · https://snyk.io/press-kit/
- https://www.tenable.com/legal · https://www.tenable.com/media
- https://www.qualys.com/company/community-terms-of-use · https://www.qualys.com/company/newsroom/media-contacts · https://www.qualys.com/legal/ **(404)**
- https://portswigger.net/web-security/certification/terms-and-conditions/website-terms-of-use · https://portswigger.net/legal
- https://1password.com/legal/terms-of-service · https://1password.com/press · https://brand.1password.com/document/45 **(not readable)**
- https://www.okta.com/legal/terms-of-service/ · https://www.okta.com/terms-of-use-for-okta-content/ · https://www.okta.com/press-room/
- https://www.vanta.com/legal · https://www.vanta.com/company/press
- https://learn.microsoft.com/en-us/legal/termsofuse · https://www.microsoft.com/en-us/legal/intellectualproperty/permissions · https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks · github.com/MicrosoftDocs/azure-docs `LICENSE`, `LICENSE-CODE`, `README.md` (cloned)
- https://developers.google.com/terms/site-policies · https://docs.cloud.google.com/security-command-center/docs/security-command-center-overview · https://partnermarketinghub.withgoogle.com/brands/google/branding-guidelines/how-to-show-googles-brand/ · https://policies.google.com/terms
- https://cursor.com/terms-of-service · https://cursor.com/brand
- https://www.youtube.com/t/terms
