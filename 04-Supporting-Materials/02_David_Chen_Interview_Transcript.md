# Interview with David Chen

**Answer:** CIO — David Chen

> **Objective:** Understand David's strategic ambition for DI, his hypotheses about the operating constraints to achieving it, how the organization is managed today, where the current model will fail at scale, and what success looks like for the Director of Operations.

## Strategy & definition of success

**Question:** If we're sitting here 18 months from now and DI has successfully scaled from ~10 to 30 people, what is meaningfully different about how the organization operates?

**Question:** Honestly, if we hit 30 people and I’m still the one chasing down James in Finance to figure out why a $40k vendor contract just auto-renewed for a tool we don't use, we’ve failed. The biggest shift is that the "tribal knowledge" phase has to be dead. Right now, if I want to know what Marcus’s pod is doing with a portfolio company, I have to go physically find him and ask—at 30 people, that just doesn't scale. Success looks like me walking in on a Monday and having total visibility into every pod’s roadmap and budget without having to hunt for it. And the onboarding—man, it's a disaster right now. We had a guy recently who couldn't even commit code for three weeks because of access issues and compliance hurdles. In 18 months, I want a new engineer productive in four days, max. Basically, I need you to build a foundation that lets Priya and Marcus stay focused on the high-level AI stuff while the "machine" of the office just runs itself in the background. Does that make sense?

**Question:** What aspects of DI’s current way of operating are most important to preserve as we scale?

**Answer:** the reason people like Priya and Marcus are here—and they could be making way more money at Google or a big consultancy—is because we don't have the "big company" sludge. We're fast. If we have an idea for a new LLM approach for clinical trials, we just start building it. I’m terrified of adding process for process’s sake. I’ve been at Amazon and Mass General, and I’ve seen how "operational excellence" can sometimes just turn into endless meetings and Jira tickets that nobody looks at. We need to keep that nimbleness where people feel they have the autonomy to just... do their jobs. So, preserve the speed and the flat structure, but give it some rails so it doesn't fly off the tracks. I want you to be the bridge to corporate—Legal, HR, Compliance—so my engineers don't have to speak "corporate" and can just stay in the zone. If you can protect their time while keeping the lights on, that’s the win.

**Question:** Where do you want DI to behave like an independent, high-velocity technology organization, and where does it need to operate as an integrated part of Deerfield Management?

**Question:** That's the million-dollar question. The high-velocity part has to be the product development and the R&D. When Priya’s team is iterating on an investment tool, I want them moving like a YC startup—fast experiments, breaking things, no layers of middle management. We need to keep that "yell across the room" energy even when we're too big to actually do that. But where we *have* to be integrated—and where we're currently struggling—is the "grown-up" stuff. We’re part of a fifteen-billion-dollar fund. We can't be "move fast and break things" when it comes to compliance, HIPAA, or how we handle sensitive clinical data. That’s where we need to be lock-step with Deerfield Management. Right now, I’m the one stuck in the middle of that friction. I spent four hours last week just back-and-forth on a single vendor contract because our tech needs didn't align with corporate procurement’s workflow. It was a total waste of time. I want the team to *feel* like they're in a lean tech lab, but I want the corporate functions—Finance, Legal, HR—to feel like we're the most organized, professional department in the building. You’re basically the translator between those two worlds. Make sense?

## Current state & hypotheses

**Question:** As you think about scaling from 10 to 30, where do you see the biggest operational constraints or failure points?

**Question:** Where do you personally spend time today that you don't think the CIO should still be spending time as the organization scales?

## DI operating model

**Question:** How do you run DI as an organization today to stay aligned on priorities, progress, decisions, and issues across the pods?

**Question:** To be totally honest? It’s a lot of "management by walking around" and ad-hoc conversations. Since we're only ten people, I can usually just grab Priya or Marcus and get a pulse on things in five minutes. We do a weekly sync, but if I'm being real, it’s not as structured as it needs to be. The problem is that "alignment" right now lives mostly in my head. I know what Priya’s doing because we talk every day, but I’d have to go digging to tell you exactly where Marcus is on his three different portfolio projects. There’s no central dashboard, no "source of truth" for our roadmap. It’s all very informal. And that’s exactly where the wheels are starting to come off. When a priority shifts—like if the investment team suddenly needs a new tool for an FDA deadline—I end up having to repeat the same context to three different people. It’s exhausting. I’m looking for you to bring some actual structure here. Not "process for the sake of process," but just... a way for me to know what’s happening without having to play detective every Tuesday. How would you even start tackling that without making the engineers feel like they're being micromanaged?

**Question:** Where do you see the greatest friction or ambiguity in DI’s current operating model?

**Question:** When priorities or interests conflict (across pods or between DI and broader Deerfield), how are those trade-offs resolved today and will that model scale?

**Question:** Right now, it's basically the "David bottleneck." If Priya needs a data engineer for an investment tool but Marcus needs that same person for a biotech portfolio company, they both come to me. I make a call based on whatever the fund's immediate priority is—usually whichever one has the tighter deadline or the bigger dollar amount attached to it. It's... not great. It’s definitely not going to scale to 30 people. I'm becoming the single point of failure for every minor resource conflict. The bigger issue is the conflict between us and the broader Deerfield corporate side. Like, I'll have a candidate we need to hire *yesterday* because they have three other offers, but HR has their own process and pace. Or Legal wants to spend three weeks redlining a $5k software license that we need to start a project tomorrow. Right now, I just jump in and use whatever political capital I have to push things through. But I can't be the "fixer" for every single friction point as we grow. I need you to build a system where these trade-offs are clearer—maybe a way to prioritize projects that everyone agrees on upfront—so we aren't just reacting to whoever is shouting the loudest that morning. What’s your take on handling that kind of friction?

**Question:** In all of my other interviews, the issues surrounding Legal have not come up. It's been concentrated to Finance (which includes procurement), HR, and Compliance. Can you walk me through who the counterpart is in legal, the major friction points with legal, and how you think the working relationship could be improved? Or is legal under the same umbrella as compliance?

**Question:** Ah, good catch. They are technically separate functions here, though they sit close together. Sarah is our main point of contact in Legal. She’s sharp, but her job is to protect the $15B fund, while my job is to move at the speed of AI. The friction usually hits when we’re dealing with two things: **vendor contracts** and **data privacy**. On the vendor side, it’s the "redline death spiral." I’ll find a niche startup tool that gives us a massive edge in analyzing clinical trial sentiment. The contract is maybe $10k. But Sarah’s team will treat it like a multi-million dollar enterprise deal, arguing over indemnity and liability clauses for six weeks. By the time it’s signed, the investment team has already moved on to a different thesis. I spent four hours last week just being a "translator" between Sarah and a vendor's CTO because they were speaking two different languages. Then there’s the data side. When we want to ingest a new healthcare dataset, Legal and Compliance both get involved, but Sarah is looking at the intellectual property and usage rights. To improve it? We need a "fast-track" process. We need pre-approved templates for low-dollar software and a way to categorize our vendors by risk so we aren't treating a Slack integration like a core banking system. I need you to be the one who sits with Sarah, understands her "must-haves," and then manages the vendors to meet those requirements so I only get pulled in for the 1% of stuff that’s actually a dealbreaker. Does that clarify why I’m feeling the heat there, even if the others didn't mention it? It's mostly a "David's time" problem.

## XFN operating model

**Question:** Which relationships with the broader Deerfield are most critical to DI's success?

**Question:** Where do you see the greatest friction in how DI works with those partners today?

**Question:** It’s definitely the "Big Four": Finance, HR, Legal, and Compliance. If those aren't working, we're dead in the water. The biggest friction right now is with Finance and HR. With Finance, it’s just a total lack of visibility. James is a good guy, but he’s spread thin. I found out last month we’d been paying for a SaaS tool for six months that literally nobody was logged into. Just... forty grand down the drain because nobody was watching the shop. Then there's HR. Elena is great, but our hiring process is a mess. We’ve been trying to land a senior ML engineer for four months. Four months! Candidates fall through the cracks, the feedback loop is slow, and by the time we’re ready to move, they’ve already taken a job at a hedge fund or a big tech firm. And don't even get me started on the "onboarding" dance with IT and Compliance. Like I mentioned, having a brilliant engineer sit there for three weeks unable to touch a keyboard because they don't have the right permissions? It’s embarrassing and it kills morale. I need you to be the person who speaks their language. When Legal wants to redline a contract for three weeks, I need you to be the one explaining the technical urgency so I don't have to spend my afternoon in a conference room arguing about indemnity clauses. You need to turn those relationships from "roadblocks" into "partners." Does that sound like something you've dealt with before?

**Question:** What do you think those partners would say is most difficult about working with DI?

## Hypothesis review and 30-day priorities

**Question:** Across the interviews, the strongest pattern I see is that DI doesn’t need significantly more process, but it does need a lightweight operating backbone that makes priorities, capacity, dependencies, ownership, and decisions more visible. Does that diagnosis feel right to you and what would you challenge about it?

**Answer:** That diagnosis is spot on. "Lightweight" is the keyword. If you come in here and try to implement a heavy Six Sigma framework or make my engineers spend two hours a week updating status reports, they’ll revolt. They’re here to build, not to be administrators. The only thing I’d challenge—or maybe just emphasize—is that "visibility" isn't just for the team; it’s for me and for our stakeholders. Right now, I’m the human dashboard. I’m the one who has to remember that Priya is waiting on a data engineer who is currently buried in a project for Marcus. That’s not a "decision" I should be making every Tuesday; it should be obvious from the system you build.

The other thing is the "ownership" piece. Right now, when something breaks—like that $40k auto-renewal or the three-week onboarding delay—it’s nobody’s job, so it becomes my job. I need this operating backbone to clearly define who owns the "non-code" parts of our success. If you can make the invisible work visible without slowing us down, you’ll be a hero.

**David follow-up:** How do you introduce that kind of visibility to a group of high-performers who are used to just "doing their own thing" without making them feel like you're breathing down their necks?

**Question:** I’ve prioritized six issues into two immediate agendas: portfolio control and delivery reliability, and hiring and onboarding readiness. If I could materially improve only those two things in the first 30 days, would you agree they create the most leverage? Or is there something else you would put ahead of them?

**Answer:** That’s a solid start. If you can actually fix the hiring and onboarding mess in the first month, you’ll win over the team immediately. They’re feeling the burnout of being shorthanded, and seeing a new hire actually work on day three instead of day twenty-one would be a massive morale boost.

On the "portfolio control and delivery" side—yes, that gives me the breathing room I need. If I can stop playing "human router" for every project update, I can actually get back to the AI strategy stuff I'm supposed to be doing.

The only thing I might nudge you to look at alongside those—or maybe as a "quick win" within the portfolio control piece—is the **vendor/spend leak**. That $40k auto-renewal still stings. If you can just get a handle on what we’re paying for and when the next five renewals are coming up, you’ll pay for your own salary in about a month. It also builds huge credibility with James in Finance if you show up with a spreadsheet of our actual tech spend before he has to come hunting for it.

But yeah, if you tackle those two agendas, you're hitting the biggest pain points. Everything else, like the long-term culture stuff or the three-year roadmap, can wait until you've stopped the bleeding.

**David follow-up:** How are you planning to handle the "pushback" if, say, Marcus feels like the new project tracking is just "extra homework"? He’s great, but he’s protective of his team’s time.

**Question:** I think that’s exactly the risk I’d want to avoid. I wouldn’t start by telling him that he has a new project tracking process. I’d start with the problem we are trying to solve and then I’d build the minimum mechanism with him rather than for him. If we need five fields, we would build five and not twenty. And wherever possible I’d pull in info from something the team already maintains rather than duplicating. I’d also want to ensure there’s a clear value exchange for Marcus. Does that make sense? One implication of the portfolio work I’d like to propose is that new demand would come through a common intake, material work would be visible in one portfolio view, and cross-pod commitments wouldn’t be made until the supplying pod has accepted the dependency. Do you think that would create unnecessary friction with Marcus based on what you’ve flagged?

**Answer:** I love the "build with him, not for him" approach. That’s exactly how you handle someone like Marcus. If he feels like he’s the architect of the solution, he’ll champion it.

Regarding the common intake and the cross-pod commitments—honestly, that’s the "good" kind of friction. Right now, the friction is invisible and results in missed deadlines or me getting a frantic Slack at 9 PM because a dependency wasn't caught. Having a pod actually accept a dependency before a commitment is made to the investment team? That’s not bureaucracy, that’s just basic physics. It protects the engineers from being over-promised.

The real test will be the "common intake." The investment team is used to just texting me or cornering Priya in the breakroom to ask for "one quick thing." You’ll need to be the "bad cop" there—or at least the "organized cop"—to make sure those requests actually go through the front door so we can track them. If you can show Marcus that this system actually protects his team from random side-quests, he’ll be your biggest fan.

**David follow-up:** We’ve covered a lot of ground. I’ve got a hard stop for a meeting with the MDs in a few minutes, but what’s the one thing you need from me to be successful in those first 30 days if we move forward?

**Question:** Clarity and visible backing on the mandate. In the first 30 days, I’m going to be asking people to change some of the ways they work—not by adding a lot of process, but by creating more visibility around priorities, ownership and commitments. I can build the mechanisms and earn adoption and relationship capital with the team over time, but I need people to understand that I’m doing that with your backing and that, when there are real trade-offs or resistance I can’t resolve directly, you’ll reinforce the mandate. If I have that, I can take care of the rest. Do I have your commitment and support on that?

**Answer:** You have it. 100%. I’ll be very clear with Priya, Marcus, and the rest of the team: you aren't here to be an assistant; you’re here to be the Director of Operations with the authority to build the foundation we need to scale. If I’m not willing to back you when things get uncomfortable, then there’s no point in you being here.

When you start, we'll sit down with the pod leads and I’ll make it explicit. I’ll tell them, "I’ve asked this person to fix our broken pipes so you guys can focus on the AI. If they ask for visibility or a change in how we track things, it’s because I’ve authorized it." I’ll have your back, but I’ll also trust you to use that "political capital" wisely. Don't spend it all on day one, but when you need the hammer, let me know.

Listen, I’ve got to jump to this MD meeting—speaking of things I’d rather you be handling!—but this was a great talk. You’ve got the right read on the situation. I’ll let the team know we’re moving to the next steps. Thanks for the candor.
