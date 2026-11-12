EngageTrack AI™ — Interactive Prototype
NOFA AI Factory™
Stage: Interactive prototype; scripted/rule-based simulation, not live predictive AI
Entry point: index.html (standalone; no build commands required)
Purpose
EngageTrack AI™ turns manually supplied engagement and relationship activity into a prioritized follow-up workspace for business owners and networking professionals. The prototype has eight integrated modules, plus a Contacts & Interactions workspace and CSV import.
The essential distinction: contact vs interaction
A person may be an existing Contact, Not connected, or Unknown. That is an explicitly maintained relationship fact, separate from their engagement. One person can have multiple interaction records (profile visits, posts, networking events, messages, meetings). The Overview includes a dedicated Known contacts with interactions count and list. A profile visit or click does not automatically make someone a contact.
Identity matching on CSV import
- Exact nonempty email address or profile URL matches an existing person.
- Exact name-only possible matches go into Unmatched / uncertain identities for user review; no silent merge.
- New individuals without a match are created and labeled Unknown unless the uploaded relationship value explicitly says otherwise.
- Unmatched records can be linked to an existing person or created as a new individual after review.
Main modules
1. ClickPredict AI™ — transparent, age-weighted Warmth Score™; ranks observed engagement.
2. NetworkNudge AI™ — editable personalized outreach templates, manually copied or saved as drafts.
3. EngageMap AI™ — heatmap by industry and interaction type.
4. AutoFollowUp AI™ — prioritized suggested follow-up actions, no actual automatic sending.
5. ClickLens AI™ — interaction volume by topic and industry.
6. SmartReferral AI™ — heuristic referral-partner fit indications.
7. EngageIQ™ — manually logged event costs, leads, meetings, customers, and revenue.
8. ConnectLoop AI™ — local follow-up schedule, check-in drafts, and reminders shown upon app opening.
Quick test walkthrough
1. Open index.html in a modern desktop/mobile browser. Fictional examples appear by default.
2. Open Contacts & Interactions, select a confirmed contact, and add an interaction. Note its influence on Warmth Score™.
3. Change Relationship from Contact to Not connected; the Overview's known-contacts-with-interactions list updates accordingly.
4. In Import Data, download the sample CSV, edit it, then import. Review unmatched name-only records before linking.
5. Open NetworkNudge, draft a follow-up, and save or copy it. No email is sent.
6. Open EngageIQ and add an event's results; the dashboard recomputes ROI.
7. Use Settings to export/restore local JSON or reset the demo.
CSV columns
name,email,profile_url,company,role,industry,relationship,interaction_type,date,topic,source,note

Supported interaction types: profile_visit, post_like, post_comment, post_share, event_attended, event_chat, message_sent, message_received, meeting_requested, meeting_held, referral_discussion, referral_received.

Use date YYYY-MM-DD. Quote CSV fields containing commas. The prototype caps file size at 2 MB.
Warmth Score™
Scores are a deterministic weighting of logged events, with recency adjustment and a 100-point cap. Example event weights: profile visit 6, comment 10, received reply 18, meeting requested 24. This is not a percentage likelihood to buy, partnership confirmation, or validated intent model.
Current prototype limitations
- Browser-only HTML/CSS/JavaScript; localStorage stores the contact and interaction demo data locally.
- No backend, authentication, permission system, cloud sync, or multi-tenant access.
- No Alignable API, scraping, Gmail integration, actual message delivery, background jobs, or real AI model inference.
- Events must be uploaded or logged. The system cannot independently observe private profile visits or tell whether an unidentified visitor is the same person as a known contact.
- Relationships and matching require manual review. No automatic external identity enrichment.
- The prototype uses fictional demo contact data. Use consent and applicable privacy rules with any real networking data.
Proposed SaaS upgrade
Add secure user/tenant authentication, consent and retention management, audited contact imports, robust identity resolution, real integrations only where authorized, supervised outreach approval, asynchronous scheduling, and—after enough outcome-labeled history—calibrated predictive models. Keep user decisions separate from model-generated suggestions.
Product summary
EngageTrack AI™ is a relationship and engagement intelligence workspace that helps business owners prioritize follow-ups, uncover referral opportunities, and measure outcomes from networking activity.
