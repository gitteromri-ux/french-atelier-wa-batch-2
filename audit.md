# French Atelier · WhatsApp Batch 2 audit

## Verdict

**No: the original Batch 2 did not meet every requirement, and it was not justified to call it an all-pass delivery.** It had the right eight subjects, body lengths and image dimensions, but there were literal brief misses, image/copy inconsistencies, insufficient sender and CTA clarity, and unverified production assumptions. The revised version corrects the identified copy and presentation defects; it is still a content handoff, not proof of an approved, configured or send-ready campaign.

**Sandra/ActiveCampaign compliance is not fully verified.** Searches of the available email, files and past conversations did not recover a complete Sandra-authored specification for this assignment. The report therefore separates retrieved historical instructions, actual Batch 1 conventions, published platform limits and operational checks that remain unverified. It does not turn past assistant assurances into Sandra’s instructions.

## What was compared

| Evidence | Exact scope |
|---|---|
| Original brief | Complete supplied document, including the embedded Rosen WhatsApp example and repeated October/November sections. The three attached copies are identical. |
| Approved Batch 1 | Eight message files, HTML/CSS, images and favicons at commit `3c377f10766046b69b295142bd8fc0a9347a40c1`; [approved gallery](https://gitteromri-ux.github.io/french-atelier-wa-8-briefs/). |
| Original Batch 2 | Immutable delivered commit `648d9b8150245643f2477b596f7f2dc065296e16`, not the subsequently edited working copy. |
| Revised Batch 2 | All eight revised bodies, individual and combined handoffs, gallery previews, brighter exports and upscaled masters. |
| Product and brand | Live [French Atelier website](https://www.frenchatelierlive.com), including its actual [white logo asset](https://www.frenchatelierlive.com/assets/logo/logo-white.png). |
| Historical requirements | User-authored instructions from the August French Atelier assignment, checked separately from assistant summaries and from the current eight-topic brief. |
| Platform rules | [Meta template components](https://developers.facebook.com/docs/whatsapp/business-management-api/message-templates/components/), not an assumed ActiveCampaign email specification. |

Statuses mean: **Met** = directly supported by inspected content or measurement; **Corrected** = original miss fixed in the revision; **Qualified** = interpretation or aesthetic judgment, not unconditional compliance; **Unverified** = missing production evidence; **Not met** = a remaining gap. “New revision request” means the later lighting/4K change, not a retroactive original-brief requirement.

## Full Q&A: the brief and the campaign goal

| Question | Original Batch 2 | Revised Batch 2 |
|---|---|---|
| Did we produce eight WhatsApps, not eight emails? | Yes. Eight separate message bodies and handoff files. | Yes. No email subject, preheader, email HTML body or email unsubscribe token has been substituted. |
| Are these new messages on the correct eight subjects? | Yes. The same eight topics as Batch 1, with new bodies. | Yes. All eight remain; none has been replaced with an unrelated subject. |
| Is the goal weekly educational engagement with the existing French Atelier base? | Partly. Cultural education was present, but sender and school context were not sufficiently clear to the user. | Explicit school identity appears near the start of every body. Cultural learning remains the main content, not a generic acquisition sales pitch. |
| Are all bodies 150-200 words? | Yes, 156-163 using the same stated counting method. | Yes. Exact counts are below; the embedded headline is now included. |
| Are Header Text and CTA Button Text supplied? | Yes, both fields existed. | Yes. The editorial headline is retained as a handoff field and appears inside the body when using an image header. |
| Are three relevant French vocabulary entries supplied? | Yes, but mostly as detached lists; Tour explicitly required in-story integration. | Yes. Tour words are integrated within the scene. The other messages use concise explanatory sentences; they are not unrelated fact inventories. |
| Is there one coherent topic in each message? | Yes, with the expressly requested promo exceptions. | Yes. No unrelated course claims or extra campaigns added. |
| Are paragraphs short and scannable? | Structurally yes; the original dark small-type presentation weakened readability. | Yes. White message surfaces, 16px preview body text, short paragraphs and bold topic/vocabulary treatment. Real WhatsApp typography is controlled by the app, not this CSS. |
| Is the tone calm, clear and supportive? | Not an unqualified pass. The user rejected the story-like copy and unclear purpose; that feedback overrides an earlier subjective “pass.” | More literal headlines, explicit sender, shorter scene-setting and low-pressure language. This is an editorial improvement, not a measurable guarantee of the user’s aesthetic approval. |
| Is immersive scene-setting retained without long storytelling? | Mostly, but the repeated literary opening formula was too prominent. | Yes, brief Notre-Dame, Montmartre, photography, exhibition, flag, museum, kitchen and mountain-road settings remain. |
| Are there complex metaphors, vague lifestyle claims or fabricated results? | No sustained complex metaphor or outcome guarantee found. Some wording felt abstract. | No invented fluency, speed-of-learning, availability or result promise. Concrete objects and activities replace abstract wording. |
| Are emojis permitted? | Yes. The brief explicitly welcomes relevant emojis. | One thematic greeting emoji per message. These are intentional brief content, not accidental marks. |
| Is there pressure or urgency? | No invented scarcity/deadline. “Claim it now” was explicitly mandated for promos. | Same. No fake limited places, countdown or expiry date. |
| Are six messages content-led, with exactly two 20% offers? | Yes, offers in 3 and 4. | Yes, separate final offer paragraphs in 3 and 4. See the brief contradiction below. |
| Is a fun fact included where requested? | Yes, one labelled block per message. | Yes, one labelled block per message; Quiche’s fact was changed to avoid the cheese contradiction. |
| Does “reassurance about trusted place” appear? | Only implicitly through teacher/class mentions; not a fully justified literal pass. | Full school identity, live-online context and low-pressure practice language are explicit. No fabricated accreditation or trust badge was added; the brief does not define a required trust claim. |
| Is prohibited selling absent from content messages? | No discounts, urgency or purchase requests in 1, 2, 5, 6, 7 and 8. School references and a website button remain light brand promotion. | Same distinction. “About French Atelier” is an informational school CTA, not a disguised lesson/story offer. Topic 8’s detailed DO NOT list does not itself include “Any selling”; we do not invent that clause. |
| Are invented teachers, lessons, resources or assets absent? | No named fake teacher. “See the full story” from Batch 1 was not reused because all buttons led to the homepage. | No fake teacher, downloadable recipe, created video, content article or offered cooking class. The Lorraine scene is explicitly imagined. |
| Are created videos, the AI Agent and the Self Service Area omitted? | Yes. Mentioning the film Amélie is not claiming a created video. | Yes. Also no “LMS” wording. |
| Are all original image exports exactly 1792 × 897? | Yes, all eight. | Yes, all eight. Larger masters are additional files, not substituted delivery dimensions. |

### The brief contains a real contradiction

The opening paragraph puts promotions in messages **4 and 8**. The numbered topic instructions put the October photography offer in **3**, the November digital-culture offer in **4**, and repeat both instructions at the end. Approved Batch 1 also uses 3/4, so Batch 2 follows those specific instructions and the approved precedent. This is a disclosed interpretation; it cannot be scored as satisfying both contradictory placements.

The repeated photography and Novembre Numérique sections are duplicates, not requests for messages 9 and 10. The embedded Rosen example demonstrates cultural content followed by a separate offer and button; its 25% grant, limited quantity and urgency are specific to Rosen and were not imported into French Atelier.

## Full Q&A: exact match to Batch 1

| Question | Answer |
|---|---|
| Was the original Batch 2 an exact presentation-format match? | **No.** It retained the same broad gallery/card/phone structure but changed content CTA labels, Notes to Production fields, footer treatment, the manifest content and responsive/phone-height behaviour. Calling it “exact” was too strong. |
| Were the original images the same files? | **Yes.** The original Batch 2’s eight image bytes match Batch 1. That is asset reuse, not eight newly generated pictures. |
| Are the revised images still byte-identical? | **No, intentionally.** The user requested substantially brighter imagery. Composition and subjects remain from Batch 1; tonal treatment and export encoding changed. |
| Did image type match? | Yes: seven illustrative photographic-style scenes and one Monet-style painting. None is presented as documentary proof, a real school class, a verified film still or an authenticated Monet reproduction. |
| Did image sizes/aspect match? | All delivery exports remain 1792 × 897. Added 4096 × 2050 masters approximate the same aspect with a negligible one-pixel rounding difference. |
| Did fonts and palette originally match Batch 1? | Yes: Cormorant Garamond/Inter and the inherited navy/gold/ivory palette. Matching Batch 1 did not establish exact equality to the live website’s logo and hex values. |
| Does the revision change branding? | It uses the actual website logo instead of a simulated text lockup and the website’s navy/cream foundation. Darker gold is used for small metadata text for readability. This is an intentional design correction, not a claim of pixel-identical Batch 1 CSS. |
| Were favicons replaced? | No. The inherited favicon assets remain unchanged. They are gallery assets, not content attached to a WhatsApp message. |
| Was the content CTA identical? | No. Batch 1: “See the full story”; original Batch 2: “Visit French Atelier”; revision: “About French Atelier.” The new label describes the actual school-homepage destination without inventing a story page. |
| Was the promo CTA identical? | Yes: “Claim it now.” Its required label does not prove that the linked homepage redeems the discount. |
| Was the first-name convention preserved? | Yes, literal `{{BODY_1}}`. This proves handoff consistency only, not compatibility with the eventual provider/ActiveCampaign configuration. |
| Was the handoff field structure preserved? | Core fields are retained: template name, Category, Code, Trigger, Header Text, CTA Button, CTA URL/Action, Word count, fenced body and Notes. New image and character measurements are explicitly additional production notes. |
| Was Batch 1 changed? | No. Changes are confined to the separate Batch 2 project. Batch 1 remains the benchmark, not an edit target. |

## Full Q&A: sender, headlines and CTA

| Question | Answer |
|---|---|
| Can a recipient tell who is speaking? | The revised body says “From French Atelier by Acadomia, your live online French school” immediately after the greeting/headline. The preview sender bar uses the same brand. The actual WhatsApp Business account/profile has not been inspected. |
| Does every headline name its subject? | Yes: Victor Hugo/Notre-Dame; Amélie/Montmartre; France/photography; Novembre Numérique; French flag; Claude Monet/water/light; quiche Lorraine; Tour de France/Pyrenees. |
| Is the content CTA’s purpose clear? | “About French Atelier” opens the school homepage, reinforced by “Find out who we are on the French Atelier website.” It does not promise a full story or asset that has not been supplied. |
| Is the promo CTA complete and usable? | **Not verified for redemption.** It says “Claim it now” as required, but still points to the homepage. No valid offer-specific destination, code, eligible-course scope, redemption behaviour or terms were established. Both promos are marked not ready for activation. |
| Did the audit invent a coupon or sales page to remove that blocker? | No. A 200 response from the homepage is not a successful discount claim and is not reported as one. |
| Is a hard-sell headline required on all eight? | No. The brief asks for educational engagement and prohibits selling on the specified content messages. Clarity was strengthened without turning the six content messages into ads. |

## Full Q&A: website and brand truth

The live site presents French Atelier by Acadomia as an online French school with live classes and native French teachers. These are supported product descriptions; the copy does not add new course durations, prices, outcomes or availability claims ([French Atelier](https://www.frenchatelierlive.com)).

| Check | Answer |
|---|---|
| Exact school identity and Acadomia attribution | Present in all eight revised bodies and preview sender bars. |
| Actual logo versus recreation | Revised gallery uses the retrieved official white PNG. Logo placement belongs to the handoff gallery, not an asserted WhatsApp-header-logo requirement. |
| Website palette versus approved gallery palette | Original gallery used navy `#0B1340`, gold `#C8A560`, ivory `#F5EFE5`; live website uses navy `#00001F`, cream `#F3EEE3`, gold accents including `#D8BC85`/`#C8A96B`. Revision adopts website navy/cream, preserves the serif/sans pairing and uses darker small-text gold for contrast. |
| Website imagery provenance | The eight campaign images are approved Batch 1 assets, not claimed to have been taken from the school website. |
| Course delivery | “Live online French school” is supported. The revision does not claim an in-person French Atelier cooking class, museum tour or festival. |
| Named teachers | None invented. |
| Discounts | 20% October/November comes from the brief, not independently verified as active on the public website. |
| Sender phone, legal entity, reply address | Not provided or verified for this WhatsApp campaign. No new contact phone or fake sender detail added. |
| Technical/platform terminology | No LMS, AI Agent or Self Service Area in customer copy. |
| Promised resources | No video, story page, recipe download, quiz, PDF lesson or self-service resource promised. |

## Full Q&A: Sandra, IIBS, ActiveCampaign and WhatsApp production

**This section is not an all-pass certificate.** The retrieved history establishes requirements to follow the previous IIBS/eTeacher WhatsApp handoff, use the website as product truth, avoid em dashes and AI-like language, name the subject clearly and distinguish WhatsApps from emails. It does not establish the complete Sandra-authored ActiveCampaign configuration for this campaign.

| Requirement or check | Evidence class | Status and answer |
|---|---|---|
| Use the earlier WhatsApp format, not email format | Retrieved user instruction + existing handoff | Met in the revised content package. |
| Template name, Category, Code, Trigger, Header, CTA, URL, count, fenced body, Notes | Existing Batch 1 / earlier handoff convention | Present. This is not a completed CRM import. |
| No em/en dashes or exclamation marks | Retrieved user instruction | Zero in the revised customer-facing bodies; checked mechanically. Ordinary hyphens in Notre-Dame, Jean Valjean context and identifiers are not em dashes. |
| Clear topic headlines and brand identity | Retrieved user instruction | Revised throughout; not a requirement invented from a model’s taste. |
| Website is source of course truth | Retrieved user instruction | Applied; no invented teacher, platform feature or class promise. |
| Do not alter ActiveCampaign fields | User-reported Sandra instruction in retrieved history | Respected. No ActiveCampaign fields or automations were edited. |
| `{{BODY_1}}` first-name token | Batch 1 convention, historically described as Bird/CP | Preserved. **ActiveCampaign/provider mapping unverified.** Not silently replaced with `%FIRSTNAME%`. |
| Field IDs, custom field meanings, segmentation and trigger logic | Not recovered for this assignment | Unverified. The human-readable “weekly drip” field is not proof of an implemented automation. |
| Sending calendar, intervals, account timezone and eligible audience | Not supplied/inspected | Unverified. “October”/“November” are content instructions, not scheduled send dates. |
| Sender number, approved display name and reply handling | Not inspected | Unverified. The gallery’s sender label is a preview. |
| Opt-in, suppression, opt-out and consent handling | Operational checks, not asserted brief wording | Unverified. Absence of a “Reply STOP” line is inherited content behaviour, not proof of compliant suppression handling. |
| URL tracking / UTM / reporting requirements from Sandra | No campaign-specific specification recovered | Unverified. No parameters invented. |
| Offer code and redemption destination | Brief gives 20% but no validated flow | Unverified for both promos; a release blocker. |
| Approved Meta/Bird template IDs and category approval | No approval receipt | Unverified. Names in the handoff are proposed content identifiers, not approval evidence. |
| Test send and personalised provider preview | No test performed | Unverified. Local HTML preview is not a real WhatsApp delivery test. |
| All Sandra requirements recovered | No | Cannot honestly certify “all Sandra ActiveCampaign requirements met.” |

Meta permits one header component whose format may be text, image, video, document or location; the original mockup visually combined separate text and image headers. The revised image-header handoff places the editorial headline inside the body and counts it there, rather than suggesting two production headers ([Meta template components](https://developers.facebook.com/docs/whatsapp/business-management-api/message-templates/components/)).

The published limits checked are 60 characters for a text header, 1,024 for the body, 25 for a URL-button label and 2,000 for its URL. UTF-16 is included as an extra conservative measurement, not a claim that Meta documents its limit using that exact counting algorithm ([Meta template components](https://developers.facebook.com/docs/whatsapp/business-management-api/message-templates/components/)).

### Requirements deliberately not imported from other assignments

The older assignment’s 100-150-word length, desktop/mobile email hero dimensions, 700px email layout, email subject/preheader fields, email unsubscribe tokens, MERCI20 coupon, placement-test CTA and double-email-CTA rules are not requirements of this eight-message brief. The current brief specifies 150-200 words and 1792 × 897 images. Rosen’s example offer terms are not French Atelier’s terms.

## Full Q&A: accuracy and imagery

| Topic | Factual check and original defect | Revised disposition |
|---|---|---|
| Hugo | Both required books and characters are appropriate; the French title is Notre-Dame de Paris. | Both works retained; plain headline and immediate sender. [Syracuse University Library](https://library.syracuse.edu/digital/guides/h/hugo_v.htm). |
| Amélie | Audrey Tautou, Montmartre and the real Café des 2 Moulins are supported; original vocabulary was relevant but not demonstrated to come from dialogue. | Uses vie, rêve and miracle, attested in the dialogue sheet; singular dictionary forms are teaching adaptations, not exact full-quote claims. [Film quotations](https://languages.org.au/french/resources/Amelie_citations_v3.pdf), [film locations](https://movie-locations.com/movies/a/Amelie.php). |
| Photography | Brief’s 1826-only wording is not undisputed; holding institution dates the earliest surviving camera photograph to 1827, ministry frames the bicentenary across 2026-2027. | “1826 or 1827” and “begins celebrating” retained as a disclosed factual qualification, not an exact literal match to 1826-only. [Harry Ransom Center](https://www.hrc.utexas.edu/niepce-heliograph/), [French Ministry of Culture](https://www.culture.gouv.fr/Media/medias-creation-rapide/celebrating-photography-bicentennial-of-photography-first-manifesto). |
| Novembre Numérique | 2026 tenth edition and French cultural network are supported. | Subject, annual timing, digital culture and separate November offer retained. [Institut français](https://www.institutfrancais.com/fr/programme/offre-contenus/novembre-numerique/novembre-numerique-2026). |
| Tricolour | Blue/red Paris and white monarchy; 1794 refers to the current arrangement, not first appearance of all colours. | Correct distinction retained. [Élysée](https://www.elysee.fr/la-presidence/le-drapeau-francais). |
| Monet | Impression, Sunrise’s title and 1874 exhibition connect to Impressionism. Original copy described that harbour painting while the image showed a lily pond/bridge. | Scene now discusses Monet’s water/light without asserting the supplied image is Impression, Sunrise or guaranteeing current museum display. Naming anecdote remains a separate fact. [Musée Marmottan Monet](https://www.marmottan.fr/en/notice/4014/). |
| Quiche | Original failed the one-sentence sensory instruction; no-cheese fact conflicted visually with cheese on the table. | One sentence now includes eggs/cream/bacon, savoury aroma, crisp crust and soft centre. Fun fact changed to historical bread-dough crust; image not claimed to be a strict ingredients diagram. [Quiche history](https://en.wikipedia.org/wiki/Quiche_Lorraine), [traditional recipe](https://www.marieclaire.fr/cuisine/quiche-lorraine,1194388.asp). |
| Tour | Original vocabulary was detached; cultural significance indirect. 1910 concerns high Pyrenean mountains, not first hills of any kind. | Vélo, sommet and maillot occur inside the story; shared summer roadside tradition is explicit; yellow correctly means overall leader. [Tour history](https://www.letour.fr/en/news/2020/the-tour-to-the-power-of-10/1283461), [classifications](https://www.letour.fr/en/the-race/sporting-stakes). |

### Are the images native 4K, and is the lighting fixed?

**The supplied larger masters are 4096 × 2050 upscales, not native 4K captures or newly generated detail.** Shadows were lifted and the eight images exported again; before/after measurements and images are supplied. This meets the larger-file dimension and brighter-treatment request, but a demand for genuinely new native-4K detail is not met by upscaling and must not be marked as met.

The original subjects remain unchanged: Notre-Dame with a hunched foreground figure; an Amélie-inspired woman in Montmartre; old/modern photography; French-feeling digital art; a flag-waving crowd; a Monet-style pond and bridge; a quiche table; mountain cyclists with yellow, green and polka-dot jerseys. The images are illustrative, so precise geography, a real actress’s identity, documentary provenance and individual crowd anatomy are not certified. The quiche still has cheese on the surrounding table; the revision removes the contradictory no-cheese teaching point rather than falsely claiming the picture was rebuilt.

## Full Q&A: visual and file QA

| Question | Verified answer |
|---|---|
| Were all eight revised messages viewed, rather than sampling one? | Yes. All eight cards were captured and inspected at 1400px desktop and 390px mobile, 16 card screenshots total. The page-level logo was separately inspected. |
| Are images, complete bodies and CTA buttons visible? | Yes, in all 16 captures. The gallery deliberately shows full-height messages rather than clipping a phone viewport. |
| Any clipped type, overlapping headings or horizontal overflow? | None found in the final screenshots or DOM overflow checks. |
| Is there one Characters metadata row per card? | Yes, eight total; no duplicated row remains. |
| Does the gallery copy match the deliverable message files? | Yes. All eight rendered bodies were compared with the individual files and combined handoff; formatting markers excluded from the rendered comparison. |
| Did all image files open? | Yes. All 16 delivery/master images were fully decoded; dimensions checked individually. |
| Were the CTA labels and destinations inspected? | Yes. Eight buttons use the school homepage; the two promo destinations remain functionally unverified for claiming an offer. |
| Is this a tested live WhatsApp message? | No. Browser and file QA do not substitute for an approved provider template or real test send. |
| Does “no AI marks” mean the images/copy are certified human-made? | No. The mechanical check establishes zero em dashes, en dashes and exclamation marks in the message bodies; it cannot certify human authorship or eliminate subjective stylistic judgments. |

## Remaining release gates

| Gate | Present status |
|---|---|
| Exact brief placement conflict | Disclosed 3/4 interpretation follows detailed instructions and Batch 1; not an unconditional literal pass of both versions. |
| Offer redemption | Both promo buttons still lack a verified discount flow. Do not activate the promos based on this gallery alone. |
| Sandra’s complete specification | Not recovered; full compliance cannot be certified. |
| Provider mapping, approved template, sender, consent and test send | Not verified or performed. No CRM state changed. |
| Native 4K detail | Not supplied. Larger masters are clearly identified as upscaled. |
| Creative acceptance | Revised lighting/design/copy have been inspected, but the user’s final taste approval is not presumed. |

The original all-pass conclusion is withdrawn. The correct conclusion is: subject coverage and measurable content/export limits pass; specific original defects are corrected; format deviations are disclosed; promotion activation and full Sandra/ActiveCampaign compliance remain unverified.


## Recomputed copy measurements

Word counting uses Unicode letter/number tokens, with apostrophe and hyphen compounds kept together. Greeting, literal name token, French vocabulary and translations count; emojis and formatting marks do not. Batch 1 and original Batch 2 counts below exclude their separate header/button fields. Revised counts include the headline now embedded in the body and exclude the external button. Character counts include spaces, newlines, emoji and the literal `{{BODY_1}}` token. The 40-character substitution test replaces that token with 40 characters; it is not a guarantee for unlimited name length.

| Message | B1 words | Original B2 words | Revised words | Revised body characters | Revised UTF-16 | With 40-character name | Headline characters | Button characters |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | 169 | 158 | 156 | 882 | 883 | 913 | 26 | 20 |
| 2 | 164 | 156 | 157 | 839 | 840 | 870 | 20 | 20 |
| 3 | 167 | 156 | 157 | 865 | 866 | 896 | 28 | 12 |
| 4 | 169 | 161 | 161 | 888 | 889 | 919 | 18 | 12 |
| 5 | 172 | 163 | 158 | 877 | 879 | 909 | 15 | 20 |
| 6 | 166 | 158 | 160 | 881 | 882 | 912 | 29 | 20 |
| 7 | 167 | 162 | 161 | 900 | 901 | 931 | 26 | 20 |
| 8 | 168 | 162 | 162 | 874 | 875 | 905 | 34 | 20 |

All revised bodies meet the 150-200-word range, remain below 1,024 both as Unicode character counts and as a conservative UTF-16 check, and remain below 1,024 with a 40-character name. Button labels are 12 or 20 characters. The headline figures remain below 60, but the headline is not configured as a second header component.

### Baseline is a visual benchmark, not proof of platform approval

| Message | Batch 1 body characters | Batch 1 UTF-16 | Original Batch 2 body characters | Original Batch 2 UTF-16 |
|---|---:|---:|---:|---:|
| 1 | 1002 | 1009 | 979 | 986 |
| 2 | 955 | 962 | 947 | 954 |
| 3 | 1001 | 1008 | 956 | 963 |
| 4 | 1079 | 1085 | 986 | 993 |
| 5 | 971 | 979 | 991 | 999 |
| 6 | 977 | 984 | 966 | 973 |
| 7 | 966 | 973 | 957 | 964 |
| 8 | 1023 | 1030 | 952 | 959 |

The original Batch 1 message 4 exceeds 1,024 literal body characters under this method. Batch 1 message 8 is 1,023 characters but 1,030 UTF-16 units; the latter is a conservative warning, not an assertion of Meta’s internal counting algorithm. Some displayed Batch 1 word counts differ from this consistently recomputed method. These observations do not modify the approved batch; they prevent inheriting an untested production assumption.

## Per-image technical and lighting audit

All eight delivery exports are JPEG, RGB, 1792 × 897. All eight additional masters are JPEG, RGB, 4096 × 2050. Brightness below is average grayscale level on a 0-255 scale, a reproducible tonal measurement rather than a guarantee of aesthetic quality or new photographic detail.

| Message / subject | Original mean level | Revised mean level | Increase | WA bytes | Upscaled master bytes |
|---|---:|---:|---:|---:|---:|
| 1: Victor Hugo and Notre-Dame | 43.56 | 100.77 | 131.3% | 938,636 | 3,894,736 |
| 2: Amélie in Montmartre | 78.18 | 118.12 | 51.1% | 925,323 | 3,854,657 |
| 3: France and early photography | 101.07 | 137.43 | 36.0% | 839,159 | 3,548,877 |
| 4: Novembre Numérique | 84.04 | 133.05 | 58.3% | 1,001,003 | 3,983,144 |
| 5: The French flag | 131.76 | 146.53 | 11.2% | 923,796 | 3,736,882 |
| 6: Claude Monet: water and light | 142.87 | 160.3 | 12.2% | 1,322,092 | 5,361,654 |
| 7: A taste of quiche Lorraine | 110.28 | 149.04 | 35.1% | 1,089,005 | 4,269,167 |
| 8: The Tour de France in the Pyrenees | 124.48 | 145.2 | 16.6% | 969,501 | 3,962,306 |

The 4K-width masters are not intended to replace the prescribed WhatsApp export. The Monet master is larger than 5 MB, so the handoff explicitly links the smaller 1792 × 897 file for WhatsApp delivery. No claim of native-4K detail, real-world capture provenance or automatic provider acceptance is made.

## Topic-by-topic revision answers

| Topic | Specific original gap or risk | Revised answer |
|---|---|---|
| Hugo | Late sender context; literary tone | Explicit school at the start, literal topic headline, both works and their human/cultural significance retained. |
| Amélie | Film vocabulary provenance unverified | Vie, rêve and miracle checked against film dialogue; Audrey Tautou and Montmartre retained. |
| Photography | Date qualification; offer destination not proven | 1826/1827 qualification disclosed; bicentenary begins in 2026; separate October 20% offer. Redemption remains unverified. |
| Novembre Numérique | School/CTA context; offer destination not proven | Tenth edition, digital creativity, three terms and separate November 20% offer retained. Redemption remains unverified. |
| Tricolour | Sender/purpose unclear | Explicit school identity and informational school CTA; Revolution and colour associations retained. |
| Monet | Harbour painting described over pond/bridge image | Describes water/light in Monet’s work; does not misidentify the illustration. Namesake painting remains a distinct historical fact. |
| Quiche | Sensory requirements spread across sentences; cheese conflict | One sentence covers ingredients, aroma, crisp/soft texture. Historical crust fact replaces no-cheese claim. |
| Tour | Detached vocabulary; weak cultural explanation | Three French terms occur in the roadside narrative; towns, families and shared summer tradition explain cultural importance. |

## Original delivery: literal topic-by-topic requirement audit

This appendix records the original, immutable delivery before the fixes above. Its “met” labels concern content coverage only; they do not overrule the user’s rejection of the original creative quality, certify a live campaign or apply to an unseen future revision. The preceding revision table records which defects were corrected.

### Topic 1  -  Victor Hugo


| Q: literal requirement | A |
|---|---|
| “Emotions to evoke: Curiosity about who Victor Hugo was, and his importance to culture” | Largely met: Notre-Dame/Quasimodo opening and explanation of literature's cultural role; emotional response cannot be guaranteed. |
| “Victor Hugo, his works, and the significance they have in French Culture today” | Met broadly: two works, their themes and present-tense cultural significance; significance is general, not richly evidenced. |
| “Introducing a little bit about his works, Les Misrables and The Hunchback of Notre-Dame” | Met: both works are named and briefly explained. |
| “3 words or phrases that is relevant, either to one of the two stories mentioned above, or that describes his work, playwrights or story or author.” | Met: un personnage, une histoire, un écrivain. |
| “Not just a list of everything he has done, but make it go with the story, it could be in a setting outside of Notre-Dame, and take the content from there.” | Met: opens outside Notre-Dame, moves to Quasimodo then the works' human themes. |
| “Images Notre Dame with The Hunch Back of Notre Dame” | Visually met: Notre-Dame and a hunched dark foreground figure. This is a stylized evocation, not verified provenance of a specific character depiction. |

Repeated requirements: 158 words; header/button present; useful words, fun fact, calm tone present; trusted-place reassurance implicit; no explicit sale, AI Agent or Self Service Area; vocabulary-list caveat applies.

### Topic 2  -  Amélie


| Q: literal requirement | A |
|---|---|
| “excitement and curiosity about who Amelie is” | Largely met: scene plus waitress quietly helping others. |
| “The meaning behind Amelie” | Partial: small moments and kindness supply a thematic interpretation, but meaning is not explicitly developed. The brief does not require explaining the character's name. |
| “How Amélie shaped an international image of Paris/French cinema” | Met briefly: colourful Montmartre became known beyond France; film shows French cinema's playful side. |
| “The movie, and the actress who play Amelie(Audrey Tautou)” | Met: 2001 film and Audrey Tautou are named. |
| “A few useful words from the movie, La vie etc.” | Partial/unverified: un quartier, un voisin, un sourire are useful and relevant; no dialogue/film evidence establishes they are from the movie. “La vie” is an example, not a mandatory exact term. |
| “Put the setting of the story in Montmartre in Paris, as its the perfect setting for this” | Met explicitly. |
| “An image of a girl with a hair style inspired by Amelie in Montmatre” | Met visually: short dark bob/fringe, Montmartre-like street and Sacré-Cœur background. |

Repeated requirements: 156 words; header/button present; real-café fun fact and supportive tone present; trusted-place reassurance implicit; no explicit sale, AI Agent or Self Service Area; list caveat applies.

### Topic 3  -  200 Years of Photography + October Promo


| Q: literal requirement | A |
|---|---|
| “campaign for October” | Met: closing offer explicitly says October. |
| “curiosity and surprise about France’s role in the history of photography” | Largely met: ordinary window view contrasted with a two-century-old experiment. |
| “In 2026, France is celebrating 200 years of photography and its French beginnings.” | Met in subject: “In 2026, France begins celebrating 200 years of photography.” |
| “Briefly Introduce the 200th anniversary of photography and its connection to France.” | Met explicitly. |
| “Briefly mention Nicéphore Niépce and the first surviving photograph from 1826.” | Substantially met, with disclosed date deviation: says “1826 or 1827” and “oldest surviving camera photograph.” Do not label this an exact literal 1826-only match or call it inaccurate without research. |
| “Include 3 simple French words connected to photography.” / “Useful French words” / “3 French words connected to photography.” | Met: un appareil photo, la lumière, une image. |
| “Keep the promotional message separate and only at the end: offer 20% off French courses, like: And if you’d like to discover more of France through its language, enjoy 20% off your French course.” | Met: separate final 20%-off October paragraph. Example wording is not mandatory. Service claims require verification. |
| “CTA button: Claim it now (in the WA template)” | Met exactly. |
| “Calm, engaging tone” | Met overall. |
| “20% promo at the end” | Met exactly. |
| DO NOT: “Long history of photography” | Met: one compact historical paragraph and short fun fact. |
| DO NOT: “Lists of inventions or photographers” | Met: Niépce/heliography only, no inventory. |
| DO NOT: “Listing up of just multiple things” | Qualified: discrete three-word list remains. |
| DO NOT: “AI Agent or Self Service Area” | Met: neither mentioned. |
| “An early photograph/camera-inspired scene with a subtle connection between historic and modern photography.” | Met visually: old box camera/photographic plate alongside modern camera and film. |

156 words; header present; correct dimensions. Repeated unnumbered October brief at the DOCX's end does not create a ninth message.

### Topic 4  -  Novembre Numérique + November Promo


| Q: literal requirement | A |
|---|---|
| “promo for November” | Met: final paragraph names November. |
| “Emotions to evoke: inform what Novembre Numérique” | Met: explains festival and digital culture. |
| “Every November, Novembre Numérique celebrates digital culture and creativity across the French cultural network and 2026 marks its 10th edition.” | Met: every November, French cultural network abroad, digital art, tenth edition in 2026. |
| “Introduce Novembre Numérique and what it celebrates.” | Met. |
| “Briefly mention how it brings together French culture, creativity and digital innovation.” | Met: interactive exhibition and artists using technology. |
| “Include 3 simple French words connected to digital culture and creativity.” / “Useful French words” | Met: un écran, créer, une œuvre; numérique also explained. |
| “End with a short, separate promotional message offering 20% off French courses, like: Every November, Novembre Numérique celebrates how digital technology is changing the way we create, experience culture, and learn. And if French is something you'd like to learn in a new way, enjoy 20% off your online French course.” | Met: separate final discount paragraph and live-online claim. Example wording is illustrative. Actual course/service claim not independently verified. |
| “CTA button: Claim it now (in the WA template)” | Met exactly. |
| “Calm, engaging tone” | Met overall. |
| “20% promo at the end” | Met. |
| DO NOT: “Long explanation of the programme or individual events” | Met: short conceptual overview, no event inventory. |
| DO NOT: “Listing up of just multiple things” | Qualified: separate three-word list. |
| “No mention of our AI Agent” / “No mention of our Self Service Area.” | Met. |
| “A modern, creative digital-art scene with a subtle French cultural feel.” | Largely met visually: visitors before luminous art displays in a French-feeling interior with Paris imagery. Interactivity is not provable from a still image. |

161 words; header present; correct dimensions. Repeated final November brief is a duplicate instruction, not a tenth message.

### Topic 5  -  Colours of France


| Q: literal requirement | A |
|---|---|
| “excitement and curiosity about the colours of France” | Largely met: lively crowd scene and colours' origin. |
| “The story behind the French Tricolour - and how blue, white and red came together.” | Met explicitly. |
| “In front of the french flag setting, again keep it immersive with a situation where you see the french flag.” | Met: flags over a town-square crowd. |
| “Very briefly tell the story of how blue, white, and red came together during the French Revolution, including the historical associations of blue and red with Paris and white with the French monarchy.” | Met: all specified associations explicitly included. |
| “3 useful French words or simple phrases naturally connected to the flag, its colours, or the setting.” | Met for relevance: un drapeau, une couleur, la liberté. Separated as a list, but this topic does not expressly say “within the story.” |
| “a sea of people waving the French flag” | Met visually: crowded scene with many tricolours. |

Repeated requirements: 163 words; header/button present; flag-arrangement fun fact and calm tone present; trusted-place reassurance implicit; no explicit sale, AI Agent or Self Service Area; list caveat applies.

### Topic 6  -  Claude Monet


| Q: literal requirement | A |
|---|---|
| “excitement and curiosity about Claude Monet” | Largely met: visual detail and naming anecdote. |
| “Claude Monet helped change the way the world looked at art. Rather than capturing every detail, he painted fleeting moments of light, colour, nature, and atmosphere - and one of his paintings even gave Impressionism its name.” | Substantially met: loose colour, changing light, momentary views and Impressionism naming all present; “changed the world” is implied rather than expressly claimed. |
| “Setting in Musée Marmottan Mone” | Met: correct museum name Musée Marmottan Monet used. |
| “Storytelling while walking thru the museum.” | Met briefly: “Walk through” then pause before a painting. |
| “3 simple French words connected to the scene, such as la lumière (light), un reflet (reflection), and un paysage (landscape).” | Met with all three example words. |
| “An image of a paiting made in same style as a Monet painting.” | Met visually: Impressionist-style water-lily garden and bridge. **Separate coherence issue:** not the harbour/sun painting described in the body. The brief did not explicitly require Sunrise as the picture. |

Repeated requirements: 158 words; header/button present; naming fun fact and calm tone present; trusted-place reassurance implicit; no explicit sale, AI Agent or Self Service Area; list caveat applies.

### Topic 7  -  Quiche Lorraine


| Q: literal requirement | A |
|---|---|
| “excitement and curiosity about french food and culture” | Largely met through preparation and tasting scene. |
| “Discover Quiche Lorraine, one of France’s best-known regional dishes, through its simple ingredients, flavours, and origins.” | Mostly met: ingredients/flavours and Lorraine location given; origins are not developed beyond regional placement. Brief does not demand a detailed history. |
| “Set the scene in a cooking class in Lorraine, with the reader preparing or tasting a traditional Quiche Lorraine.” | Met explicitly: reader presses pastry, observes baking and tastes. |
| “Use one sensory sentence to capture the quiche’s ingredients, aroma, and texture.” | **Not met literally.** Ingredients occur in the opening paragraph; aroma in “As the quiche bakes…”; texture in “Your first bite brings crisp edges and a soft, creamy centre.” No single sentence contains all three. |
| “Include 3 useful French words connected naturally to the experience, such as la pâte (pastry), les œufs (eggs), and la crème (cream).” | Met for relevance and count: all example words used. Natural integration is partial because these are extracted into a list. |
| “Include one short fun fact about the traditional Quiche Lorraine or its origins.” | Present: traditional version is without cheese. External fact accuracy not checked in this audit. |
| “A picture of a table with a Quiche Lorraine.” | Broadly met visually: quiche on table. **Coherence flag:** large cheese wedge and grated cheese placed beside it undermine the no-cheese teaching point. Image alone cannot establish filling ingredients or prove cheese is baked into it. |

Repeated requirements: 162 words; header/button present; useful words, fun fact and supportive tone present; trusted-place reassurance implicit; no explicit sale, AI Agent or Self Service Area; list caveat applies.

### Topic 8  -  Tour de France


| Q: literal requirement | A |
|---|---|
| “excitement and curiosity about the cycle, a French icon” | Largely met: roadside applause, riders and distinctive jerseys. |
| “The Tour de France is one of France’s most iconic sporting traditions.” | Partial: Tour and shared spectator tradition are described, but its iconic place in French culture is not directly stated/explained. |
| “Set the scene during a Tour de France mountain stage in the Pyrenees.” | Met explicitly. |
| “Explain briefly why the Tour is iconic in French culture.” | Partial: families/friends gathering and outdoor togetherness imply cultural significance; jersey classification receives more space than the requested explanation. |
| “Add 3 simple French words naturally within the story.” | **Not met literally / partial overall:** un vélo, un sommet and un maillot are present but in a detached vocabulary list, not within the story. |
| “Include one interesting fun fact.” | Present: first high-Pyrenees stages in 1910. Accuracy not independently checked here. |
| “A bunch of cyclist up in the pyrinees, have one wearing the polka dot jersey, one with the yellow, and one with the green as part of the field of cyclists up the hill.” | Met visually for mountain peloton and all three requested jerseys. Precise Pyrenees geography and road ascent cannot be conclusively authenticated from the stylized image alone. |

Repeated requirements: 162 words; header/button present; useful vocabulary, fun fact and calm tone present; trusted-place reassurance implicit; no AI Agent or Self Service Area. No promo appears, satisfying detailed 3/4 placement but conflicting with opening-summary 4/8. Do not invent a topic-8 “no selling” prohibition.

