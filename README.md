Hello! My name is Thomas Athey.

I'm an entrepreneur and operator working at the intersection of music and technology. I founded a venture-backed music tech startup, and now run Creative Value, a music services company providing fractional operations and systems support to independent music businesses.

You can reach me at thomas@creativevalue.co

🟢 Active Projects

-Client-Manager Agent — Client: 6149 (music distributor) / 22TWENTY Records

A distributor like 6149 lives and dies by client email. The same questions about release timing, playlist pitching, royalties, and profile fixes, answered over and over by a small team. When the person who ran most of that inbox departed, years of institutional knowledge risked walking out with him. This is an AI client-manager agent that reads the live Gmail inbox, triages what actually needs a reply, and drafts responses in the operator's own voice — grounded in 6149's current pricing and process facts and a searchable archive of ~45,000 past client emails it pulls from for precedent. A human always reviews and sends; the agent never sends on its own. That keeps 6149's "real people, not bots" promise intact while cutting the repetitive volume.

The agent is drafting against the live inbox today. I'm currently tightening draft quality by comparing its output against the operator's actual sent replies, and building toward a company-owned version that runs on a schedule and survives any one person leaving.

Stack: Claude (Anthropic API) · Claude Code · Gmail API · Google Drive API · SQLite (FTS5 full-text search) · Python

---
Future features:

- Scheduled, headless operation — moves from on-demand (run manually) to an automated service that triages and pre-drafts the inbox on a cadence.
- Company-owned auth & handoff — replaces the personal account connection with a company service account so the system, and the inbox knowledge, belong to 6149 rather than any individual operator.
- Portal/API integration (AudioSalad) — gives the agent real-time visibility into delivery and release status, so drafts can confirm facts ("your song is delivered, live by 7/2") instead of hedging.
- Native Gmail triage labels — surfaces priority directly in the inbox the team already uses.

-Tour Advance Automation - Initial Client: Tour Manager of Pigeons Playing Ping Pong (PPPP)

Tour managers spend a significant chunk of their time on repetitive, manual work — taking venue advance emails, flight info, hotel confirmations, rental car reservations, and more, copying it all into a 70-column spreadsheet, then manually re-entering that same data into a project management tool so the rest of the team can actually read it. This tool eliminates that. It's built in Google Apps Script so no existing workflows need to change — they're just automated.

The MVP is shipped and the (PPPP) team is actively using it. I'm currently iterating toward a stable v1, and once it's there, the goal is to get it in front of other tour managers.

Stack: Google Apps Script · Gmail API · Trello API · Anthropic API (Claude)

🟡 On Standyby

-Pocket Manager: A weekly task planner for independent artists releasing music.

Built for artists who struggle with structure and follow-through during a release cycle — whether from overwhelm, or just not knowing what to do next. The dashboard gives them a single week's worth of tasks at a time, nothing more. Drag-and-drop scheduling, inline task creation, completion animations.

Currently on pause as other work has taken priority.

Stack: Next.js · React · Tailwind CSS

🔴 Past Projects

-Admin Dashboard: A catalog management platform for music rights holders.

Rights holders' ownership data largely lives in spreadsheets — and managing that data is tedious, error-prone work. These aren't financial analysts; they're people in the music business juggling splits, registrations, and publishing admin across tabs that were never designed for it. The Admin Dashboard was built to pull that data into a clean, structured UI that makes edits and new entries far easier to manage.

After talking to potential customers, I realized everyone's spreadsheet setup is different, and those setups are deeply embedded in how they work. Migrating someone off that, especially when the data is sensitive ownership and publishing information, requires significant trust, onboarding investment, and security infrastructure that takes real time to build right. At an indie SaaS price point, the effort to value didn't make sense.

Stack: Next.js · React · Tailwind CSS · Supabase

-Mesa Contracts: A contract builder for music creators and their teams  

*Oversaw product strategy and managed a full-time developer and part-time designer — not writing code at this stage.*

Music creators and their teams have always needed contracts — splits agreements, work-for-hire deals, producer agreements — but attorneys were charging hundreds of dollars for what were effectively fill-in-the-blank templates. Mesa Contracts automated that. Users could generate the right contract in minutes, use AI to make edits, and fully execute it through a built-in e-sign integration, for $5 per contract.
When we started, it wasn't obvious that the major AI companies would move aggressively into compliance-heavy areas like law. GPT and its peers got (and are getting) very good at generating simple contracts, exactly the ones we were building, and they did it cheap enough to make our unit economics hard to justify. Ultimately, it's a good outcome for musicians: democratized access to affordable legal tools. We just weren't the ones who got to build it.

Stack: Stack: Next.js · Supabase · Zustand · Stripe · OpenAI · Google Gemini · OpenSign · Pinata (IPFS) · Twilio · Resend
