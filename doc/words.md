# Risktionary - Word Dictionary

Each entry below follows the schema:

- **Word** - presented to the drawer
- **Synonyms** - accepted alternate guesses
- **Description** - rich markdown shown after the round (intro, examples, consequences, mitigation, image)
- **AI Context** - short, neutral context sent to the AI so it interprets the risk the same way players do
- **Ideas** - drawing prompts for a stuck player

---

## 1. Injury

**Word:** Injury

**Synonyms:**   physical harm, workplace injury, accident, RSI, hurt

**Description:**

Injury is one of the oldest and most universal risks in any workplace or activity - the chance that someone gets physically hurt while doing their job. It doesn't have to be dramatic: most workplace injuries build up slowly, from years of bad posture or a cluttered walkway, rather than a single dramatic accident. In software teams especially, injury risk is easy to overlook because the work looks "safe" - you're just sitting at a desk - but the body pays a price for long, sedentary hours all the same.

![Workplace safety sign](https://images.unsplash.com/photo-1584515933487-779824d29309?w=600)

### Examples
- Repetitive strain injury (RSI) from long hours at a keyboard or mouse
- A trip or fall over cables in a cluttered office or lab
- Eye strain, headaches, or back pain from poor desk ergonomics
- Wrist or shoulder pain from an unsupported laptop setup
- Burnout-related physical symptoms from prolonged crunch periods

### Consequences
- Time off work or study, reduced short-term productivity
- Chronic, long-term health impacts if untreated (e.g. permanent RSI)
- Legal and liability exposure for an employer or institution
- Reduced morale if injuries are seen as "just part of the job"
- Financial cost of medical treatment or workplace compensation

### Mitigation
Good ergonomics (monitor height, chair support, keyboard/mouse position), regular movement breaks, proper safety training for physical workplaces, and a team culture that treats rest and posture as part of doing the job well - not an afterthought.

**AI Context:** Injury = physical harm to a person during work/study (e.g. RSI, falls, strain), ranging from minor to severe, usually linked to poor ergonomics, unsafe environments, or overwork.

**Ideas:**
- A person with a bandaged arm sitting at a desk
- A wrist in a brace resting on a keyboard
- A warning/caution sign next to a slippery floor
- A crutch leaning against an office chair

---

## 2. Earthquake

**Word:** Earthquake

**Synonyms:** natural disaster, quake, seismic event

**Description:**

Earthquakes represent a category of risk that no team can control or predict - a sudden, external event that can undo weeks of planning in seconds. For teams based in seismically active regions like Christchurch, this isn't a hypothetical: physical offices, hardware, and even team members' availability can all be disrupted without warning. In a broader sense, "earthquake" stands in for any large, sudden, external disaster a project has to be resilient against.

![Earthquake damage](https://images.unsplash.com/photo-1584655933484-1c5b46f1cf2c?w=600)

### Examples
- A server room suffering physical damage, taking production systems offline
- An office building being evacuated or condemned mid-project
- Loss of physical documents, whiteboards, or on-site hardware
- Team members displaced or unable to work due to damage to their homes
- Power and internet outages across an entire city or region

### Consequences
- Risk to life and safety, injuries
- Extended infrastructure and data center outages
- Long, costly recovery timelines and economic disruption
- Loss of unsaved or unbacked-up work
- Delayed deadlines that are completely outside the team's control

### Mitigation
Earthquake-resistant building codes and office selection, cloud-based and off-site backups, distributed/remote-friendly team setups, early-warning systems, and having a documented disaster recovery and business continuity plan.

**AI Context:** Earthquake = a natural disaster risk causing physical/infrastructure damage and potential loss of life; in a project context, usually framed as a disaster-recovery/business-continuity risk that is outside the team's control.

**Ideas:**
- Cracked ground with a building falling over
- A Richter scale needle spiking off the chart
- A shaking building with visible cracks in the walls
- A collapsed bookshelf or fallen server rack

---

## 3. Data Loss

**Word:** Data Loss

**Synonyms:** lost data, data breach (related), corrupted files, wiped database

**Description:**

Data loss is one of the most common and preventable risks in software development, yet it still catches teams out constantly. It's the moment a project's most valuable, hardest-to-replace asset - its data - disappears, whether through a careless command, a failing drive, or someone else's malicious intent. Because so much of modern work only exists digitally, losing it can feel like losing months of effort in an instant.

![Broken hard drive](https://images.unsplash.com/photo-1591370874773-6702e8f12fd8?w=600)

### Examples
- Accidentally dropping or truncating a production database table
- A laptop hard drive failing with no recent backup
- A ransomware attack encrypting company or personal files
- Overwriting a file with `git push --force` or a bad merge
- Losing access to a cloud account with no local copy of the data

### Consequences
- Lost productivity and significant rework
- Direct financial cost of recovery efforts or ransom demands
- Reputational damage and loss of customer or client trust
- Legal consequences if the lost data included protected user information
- Team morale hit from losing "months of work" overnight

### Mitigation
Regular automated backups (following something like the 3-2-1 rule: three copies, two media types, one off-site), version control for code, strict access controls, and periodically testing that backups actually restore correctly.

**AI Context:** Data Loss = losing important digital information through technical failure, human error, or malicious attack; commonly discussed alongside backups and version control as prevention.

**Ideas:**
- A trash can with important files falling into it
- A cracked or smoking hard drive
- A cloud icon with a big red X through it
- A padlocked folder (representing ransomware)

---

## 4. Bus Factor

**Word:** Bus Factor

**Synonyms:** knowledge silo (related), single point of failure, key person risk

**Description:**

The "bus factor" is a darkly humorous but very real project risk: how many team members would need to be "hit by a bus" (i.e. suddenly and permanently unavailable) before the project is in serious trouble? A low bus factor means the whole team's progress hinges on one or two people's heads - their knowledge, their access, their habits - and nobody else could easily step in.

![Bus](https://images.unsplash.com/photo-1570125909232-eb263c188f7e?w=600)

### Examples
- Only one developer understands how the deployment pipeline works
- One team member holds the only copy of an API key or admin password
- A team member leaves the company and no one else understands the legacy module they built
- Only one person knows the login details for a crucial third-party service
- A sole "database person" who nobody else can query around

### Consequences
- The project stalls while others try to relearn lost knowledge
- Critical systems or credentials become inaccessible
- Onboarding a replacement takes far longer than expected
- Deadlines slip because work can't be redistributed easily
- Increased pressure and burnout risk on the "key person" who can never take time off

### Mitigation
Thorough documentation, pair programming and code reviews, shared credential vaults (e.g. a password manager), and deliberately cross-training more than one person on critical systems.

**AI Context:** Bus Factor = risk that critical project knowledge or access is concentrated in one person; if they leave or become unavailable, the team loses that knowledge or access and progress stalls.

**Ideas:**
- A bus driving away while a confused team watches
- A single key held tightly by one stick figure
- A lightbulb floating above one head, dark above everyone else's
- A "single point of failure" chain with one thick link and the rest thin

---

## 5. Swine Flu

**Word:** Swine Flu

**Synonyms:** pandemic, epidemic, viral outbreak, illness outbreak

**Description:**

Swine flu stands in for the broader risk of illness or a widespread outbreak disrupting a team's ability to work. It's a reminder that people are not machines - a wave of sickness moving through a team can rapidly shrink available capacity, and depending on the severity, can shut down entire offices, campuses, or cities for extended periods, as seen in real pandemics.

![Face masks](https://images.unsplash.com/photo-1584634731339-252c581abfc5?w=600)

### Examples
- A team losing several members to illness during a critical sprint
- Office or campus closures during a serious outbreak
- Communication and collaboration breaking down when multiple people are isolating
- Reduced availability of key stakeholders or clients during a health crisis
- Long-term "long flu"-style effects reducing a person's productivity even after recovery

### Consequences
- Sharply reduced team capacity at short notice
- Delayed deadlines and rescheduled milestones
- Increased strain and workload on the remaining healthy team members
- Broader disruption to supply chains, meetings, or in-person events
- Difficulty planning around an unpredictable timeline for recovery

### Mitigation
Encouraging good hygiene practices, supporting remote-work capability, cross-training so no single person's absence stalls work, and building realistic contingency buffers into project timelines.

**AI Context:** Swine Flu = stand-in for pandemic/illness-outbreak risk - team capacity is reduced due to widespread sickness, causing project delays and increased pressure on remaining members.

**Ideas:**
- A pig wearing a thermometer
- A face mask hanging on a doorknob
- A calendar with several days marked "sick"
- An empty office with tumbleweeds

---

## 6. Workload

**Word:** Workload

**Synonyms:** overwork, too much work, burnout (related), overcommitment

**Description:**

Workload risk is about balance - or the lack of it. Every person and team has a limit to how much they can sustainably take on, and when that limit is exceeded, the quality of the work and the wellbeing of the people doing it both start to suffer. Unlike some risks on this list, workload is often self-inflicted or driven by unrealistic expectations, which makes it one of the more preventable - and more commonly ignored - risks in software projects.

![Person overwhelmed with paperwork](https://images.unsplash.com/photo-1541560052-5e137f229371?w=600)

### Examples
- One team member assigned three major features to deliver at once
- Constant overtime leading up to a deadline becoming the norm rather than the exception
- Underestimating how long tasks will take when planning a sprint
- A student juggling coursework, a part-time job, and a capstone project simultaneously
- Saying "yes" to every request without pushing back on capacity

### Consequences
- Burnout, chronic stress, and reduced job or team satisfaction
- Lower-quality work and a higher rate of bugs or mistakes
- Increased team member attrition or disengagement
- Physical and mental health impacts over time
- A vicious cycle where mistakes from overwork create even more work

### Mitigation
Realistic task estimation, even distribution of work across the team, regular check-ins on capacity, saying no (or "not yet") to extra scope, and genuinely respecting work-life balance rather than just paying lip service to it.

**AI Context:** Workload = risk of assigning too much work to a person or team relative to their capacity, leading to stress, burnout, and lower-quality output.

**Ideas:**
- A person buried under a tall stack of papers
- A set of scales tipping heavily to one side
- A stressed stick figure surrounded by sticky notes
- A juggler with too many balls in the air

---

## 7. Sleeping In

**Word:** Sleeping In

**Synonyms:** oversleeping, missed alarm, late arrival

**Description:**

Sleeping in is a small, everyday risk that everyone can relate to - but its impact scales with how much depends on you being awake and present. A single missed alarm can mean a missed stand-up, a missed exam, or a missed deployment window, and the ripple effects can extend well beyond the person who overslept.

![Alarm clock](https://images.unsplash.com/photo-1495364141860-b0d03eccd065?w=600)

### Examples
- Missing a daily stand-up meeting or a client demo
- Sleeping through a scheduled production deployment window
- Being late to submit an assignment because an alarm didn't go off
- Missing an exam or test due to oversleeping
- Arriving late to a group presentation, leaving teammates to cover for you

### Consequences
- Missed deadlines, meetings, or exams
- A negative impression left on teammates, lecturers, or clients
- Knock-on delays for others who were waiting on you to start or contribute
- Lost marks or opportunities that can't always be recovered
- Erosion of trust if it becomes a repeated pattern

### Mitigation
A consistent sleep schedule, multiple reliable alarms (including one out of arm's reach), good sleep hygiene, and building in buffer time before anything genuinely critical.

**AI Context:** Sleeping In = personal risk of missing commitments due to oversleeping; a minor but recurring cause of missed deadlines, meetings, or exams.

**Ideas:**
- An alarm clock mid-air after being thrown or switched off
- A person fast asleep with bright sunlight streaming through the window
- A clock face showing a very late time, like 11am
- Someone sprinting out the door half-dressed

---

## 8. Arguments

**Word:** Arguments

**Synonyms:** conflict, disagreement, team conflict, dispute

**Description:**

Arguments are an interpersonal risk that most teams eventually face, especially under the pressure of tight deadlines or high-stakes decisions. Disagreement itself isn't inherently bad - healthy debate can lead to better decisions - but when it turns personal or goes unresolved, it can quietly poison a team's ability to work together.

![Two people arguing](https://images.unsplash.com/photo-1573497491208-6b1acb260507?w=600)

### Examples
- A disagreement over architecture decisions escalating into a personal dispute
- Miscommunication about task ownership causing friction between teammates
- Personality clashes affecting how comfortable people feel speaking up
- Repeated code review disagreements that never actually get resolved
- Conflict over unequal contribution to group work

### Consequences
- Decreased team morale and psychological safety
- Reduced productivity as people avoid working together
- Team members disengaging, going quiet, or eventually leaving the project
- Slower decision-making as conflicts stall progress
- Damaged relationships that outlast the project itself

### Mitigation
Fostering open communication from the start, encouraging active listening and empathy, agreeing on a clear conflict-resolution process, and addressing tension early before it festers.

**AI Context:** Arguments = interpersonal conflict within a team that risks morale, collaboration, and productivity if left unresolved.

**Ideas:**
- Two speech bubbles crashing into each other like lightning bolts
- Two people with angry faces standing nose to nose
- A broken handshake
- A tug-of-war rope about to snap

---

## 9. Lack of Knowledge

**Word:** Lack of Knowledge

**Synonyms:** knowledge silo, information gap, skills gap, not knowing

**Description:**

Lack of knowledge - sometimes called a "knowledge silo" - happens when important information gets trapped with one person or a small group instead of flowing freely through a team. It's subtly different from the bus factor: rather than being about a person's *absence*, this risk is about how information is *shared* (or isn't) day-to-day, even when everyone involved is present and available.

![Isolated silo](https://images.unsplash.com/photo-1500382017468-9049fed747ef?w=600)

### Examples
- Only the tech lead fully understands how the CI/CD pipeline is configured
- New team members never told about important past architectural decisions
- Documentation existing somewhere, but nobody knowing it's there or how to find it
- One department understanding a business rule that developers never hear about
- Tribal knowledge passed on by word of mouth and easily lost over time

### Consequences
- Reduced collaboration and duplicated effort
- Slower workflows as people rediscover things that were already known
- Poor decision-making based on incomplete information
- Repeated mistakes that someone else could easily have warned about
- New team members taking much longer to become productive

### Mitigation
Promoting cross-functional collaboration, maintaining shared and discoverable documentation, running regular knowledge-sharing sessions, and normalizing "write it down" as part of how the team works.

**AI Context:** Lack of Knowledge = information or expertise trapped with one person or group instead of being shared, hurting team decision-making, collaboration, and onboarding.

**Ideas:**
- A locked book or vault with a question mark on it
- One person glowing with a lightbulb while others stand in the dark
- A silo (grain tower) surrounded by a fence
- A puzzle piece hidden behind someone's back

---

## 10. Procrastination

**Word:** Procrastination

**Synonyms:** putting off, delaying, avoidance, dawdling

**Description:**

Procrastination is the all-too-familiar habit of delaying important tasks in favor of easier, more comfortable, or more immediately rewarding ones. It's rarely about laziness - more often it's driven by a task feeling overwhelming, unclear, or unpleasant - but whatever the cause, the deadline doesn't move just because the work was delayed.

![Person distracted by phone instead of working](https://images.unsplash.com/photo-1512314889357-e157c22f938d?w=600)

### Examples
- Leaving an assignment or report until the night before it's due
- Repeatedly postponing a difficult conversation or decision
- Scrolling social media instead of starting a task that feels daunting
- Cleaning the entire house instead of studying for an exam
- Telling yourself "I'll start tomorrow" for several days in a row

### Consequences
- Rushed, lower-quality work produced under unnecessary time pressure
- Increased stress and anxiety as deadlines approach
- Missed deadlines entirely in the worst cases
- Guilt and a damaged sense of self-trust over time
- A snowball effect where delayed tasks pile up on top of each other

### Mitigation
Breaking large tasks into smaller, less intimidating steps, creating a structured schedule with mini-deadlines, and building in accountability - such as checking in with a teammate or mentor.

**AI Context:** Procrastination = habitually delaying tasks in favor of easier or more comfortable activities, leading to rushed work, stress, and missed deadlines.

**Ideas:**
- A clock with the word "later" scrawled on its face
- A to-do list where the same one item keeps being rewritten at the top
- A person lounging on a couch while a deadline looms on a wall calendar
- A snowball rolling downhill, growing bigger

---

## 11. Poor Planning

**Word:** Poor Planning

**Synonyms:** bad planning, lack of planning, disorganization, no roadmap

**Description:**

Poor planning is what happens when a project moves forward without a clear map of where it's going. It's rarely a single bad decision - more often it's an accumulation of unclear goals, missed dependencies, and a "we'll figure it out as we go" attitude that eventually catches up with the team, usually at the worst possible time.

![Messy whiteboard](https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?w=600)

### Examples
- Starting development without a clear scope, requirements, or definition of "done"
- No milestones set, so progress issues aren't noticed until it's too late to fix them
- Underestimating how tasks depend on one another (e.g. backend needing to finish before frontend can integrate)
- Skipping a proper kickoff or planning meeting to "save time"
- No contingency time built in for things going wrong

### Consequences
- Missed deadlines and unmet project goals
- Wasted time, effort, and resources on rework
- Growing frustration and decreased team efficiency
- Loss of stakeholder or client confidence
- A stressful, chaotic finish to what could have been a smooth project

### Mitigation
Setting clear objectives and success criteria up front, regularly reviewing progress against a plan, mapping out task dependencies, and being willing to adjust the plan as new information comes in.

**AI Context:** Poor Planning = inadequate upfront planning - unclear goals, missing milestones, or unaccounted-for dependencies - leading to inefficiency, missed deadlines, and rework.

**Ideas:**
- A tangled, chaotic map with no clear route drawn
- A calendar with every single task crammed into the very last day
- A house of cards mid-collapse
- A ship steering with no compass

---

## 12. Last Minute Integration

**Word:** Last Minute Integration

**Synonyms:** big bang integration, rushed merge, eleventh-hour integration

**Description:**

Last minute integration happens when separately-built pieces of a project are only brought together right before a deadline, instead of being tested together throughout development. It's a classic trap: each part might work perfectly in isolation, but the moment they're combined, previously invisible incompatibilities suddenly become very visible - usually with no time left to fix them properly.

![Puzzle pieces not fitting](https://images.unsplash.com/photo-1611746872915-64382b5c2a98?w=600)

### Examples
- Merging several long-lived feature branches for the first time the night before submission
- Two teams discovering their APIs are incompatible only at the deadline
- A frontend and backend that were never run together until the final demo
- Database schema changes conflicting between two developers who worked in isolation
- Assuming "it'll probably just work" instead of testing integration early

### Consequences
- Merge conflicts, unexpected bugs, and integration failures
- Extreme stress and pressure in the final hours before a deadline
- A lower-quality final product due to rushed, last-minute fixes
- Features being cut entirely because there's no time to fix integration issues
- Damaged trust between subteams who each blame the other

### Mitigation
Continuous integration practices, frequent smaller merges throughout development, and setting interim integration milestones well before the final deadline so problems surface early, when there's still time to fix them.

**AI Context:** Last Minute Integration = risk of only combining project components right before a deadline instead of integrating continuously, causing errors, cut features, and stress.

**Ideas:**
- Two puzzle pieces being forced together even though they don't fit
- A clock at 11:59 with wires being frantically connected
- Two gears grinding against each other, sparks flying
- A car being assembled seconds before a race starts

---

## 13. Motivation

**Word:** Motivation

**Synonyms:** lack of motivation, demotivation, low morale, disengagement

**Description:**

Motivation is the fuel that keeps people going, especially through the long middle stretch of a project once the initial excitement has worn off and the final deadline still feels far away. A dip in motivation is one of the quieter risks on this list - it doesn't announce itself the way a bug or an outage does, but it steadily drains the energy a project needs to succeed.

![Deflated person at desk](https://images.unsplash.com/photo-1499750310107-5fef28a66643?w=600)

### Examples
- Losing interest in a project partway through a long semester
- A team member disengaging after receiving harsh or unclear feedback
- No visible reward, recognition, or sense of purpose in day-to-day tasks
- Doing repetitive, unglamorous work for a long stretch with no acknowledgment
- Comparing your progress unfavorably to others and feeling discouraged

### Consequences
- Reduced performance, effort, and output quality
- Missed opportunities to contribute ideas or catch problems early
- Lower overall satisfaction with the work and the team
- Increased likelihood of eventually disengaging entirely or quitting
- A motivation dip in one person can spread and affect team mood

### Mitigation
Setting clear, meaningful goals, celebrating small wins along the way, providing genuine recognition, and building a supportive environment where people feel their contribution matters.

**AI Context:** Motivation = the drive to complete work; low motivation risks reduced performance, disengagement, and missed deadlines, often building up gradually over a long project.

**Ideas:**
- A wilted plant sitting on a desk
- A carrot dangling on a stick, just out of reach
- A phone battery icon at 1%
- A deflated balloon

---

## 14. Lack of Common Knowledge

**Word:** Lack of Common Knowledge

**Synonyms:** jargon, acronyms, miscommunication, unclear terminology

**Description:**

This risk covers the confusion that happens when people assume everyone shares the same background knowledge - using acronyms, jargon, or shorthand that not everyone in the room actually understands. It's an easy trap to fall into, especially for experienced team members who've used certain terms so often they forget not everyone speaks the same "language."

![Confused person with question marks](https://images.unsplash.com/photo-1607083206968-13611e3d76db?w=600)

### Examples
- Using an internal acronym in a meeting with new stakeholders who've never heard it
- Assuming a junior developer already knows an "obvious" industry-standard term
- Technical jargon confusing a non-technical client during a demo
- A lecturer using shorthand that only some students in the class understand
- Two teams using the same word to mean two completely different things

### Consequences
- Wasted time going back to clarify what was actually meant
- Incorrect interpretations leading to mistakes or wrong deliverables
- Frustration and a feeling of being left out or talked over
- Reduced trust and willingness to speak up ("everyone else seems to get it")
- Onboarding taking longer than it needs to

### Mitigation
Using clear, plain language wherever possible, explaining acronyms and jargon the first time they're used, and actively encouraging people to ask questions without fear of looking uninformed.

**AI Context:** Lack of Common Knowledge = miscommunication that arises from assuming everyone understands the same jargon, acronyms, or terminology, causing confusion or errors.

**Ideas:**
- A jumble of random letters (acronym soup) with question marks floating around
- Two people with speech bubbles full of gibberish aimed at each other
- A dictionary with a confused face drawn on the cover
- A single lightbulb over one head in a room full of blank stares

---

# New Suggested Words **(NEW - please review)**

## 15. Scope Creep

**Word:** Scope Creep

**Synonyms:** feature creep, expanding requirements, moving goalposts

**Description:**

Scope creep is the slow, often well-intentioned expansion of a project's requirements beyond what was originally agreed - usually without a matching increase in time, budget, or people. It rarely feels dangerous in the moment ("it's just one more small feature"), which is exactly what makes it so easy to fall into and so hard to notice until the deadline is suddenly at risk.

![Expanding scope illustration](https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?w=600)

### Examples
- A client repeatedly asking for "just one more feature" after requirements were signed off
- A team adding polish or nice-to-have features instead of finishing the agreed core requirements
- Requirements quietly changing mid-sprint without anyone re-planning the timeline
- A supervisor's expectations growing over the course of a project without formal agreement
- "While we're at it" additions that each seem small but add up significantly

### Consequences
- Missed deadlines and ballooning costs or effort
- Team burnout from chasing a constantly shifting target
- Core features being rushed or cut to make room for new additions
- Difficulty ever calling the project "finished"
- Strained relationships with stakeholders when expectations aren't managed

### Mitigation
Getting clear requirements sign-off before starting, using a formal change-control process for new requests, and being willing to say "not now" or "in a future version" to new asks.

**AI Context:** Scope Creep = requirements expanding beyond the original plan over time without adjusting timeline or resources, risking delays, cut corners, and burnout.

**Ideas:**
- A balloon inflating well past its safe limit
- A goalpost being wheeled further away as a player runs toward it
- A to-do list that keeps growing new items faster than they're crossed off
- A suitcase that won't close because too much has been packed in

---

## 16. Technical Debt

**Word:** Technical Debt

**Synonyms:** shortcuts, quick fixes, legacy code, hacky code

**Description:**

Technical debt is a metaphor borrowed from finance: just like a financial loan, taking a shortcut in code now can save time today, but it comes with "interest" that has to be paid back later - usually in the form of slower development, more bugs, and harder maintenance. A little debt, taken on deliberately, can be a reasonable trade-off; too much debt, left unpaid, can eventually cripple a project.

![Tangled cables representing messy code](https://images.unsplash.com/photo-1518770660439-4636190af475?w=600)

### Examples
- Hardcoding values instead of building a properly configurable system
- Skipping automated tests to ship a feature faster
- Copy-pasting code in multiple places instead of refactoring into a shared function
- Leaving a "TODO: fix this properly later" comment that never gets addressed
- Choosing an outdated library because it was familiar, rather than a better long-term option

### Consequences
- Increasingly slow, error-prone development as the codebase grows
- Harder onboarding for new developers trying to understand messy code
- Small changes becoming disproportionately risky and time-consuming
- Bugs that are hard to trace back to their root cause
- Eventually requiring a costly, disruptive rewrite

### Mitigation
Scheduling regular refactoring time, enforcing code review standards, tracking known debt explicitly (rather than hiding it), and consciously balancing short-term speed against long-term maintainability.

**AI Context:** Technical Debt = the accumulated cost of shortcuts or quick fixes taken in code, which slows future development and increases bugs unless it's actively addressed through refactoring.

**Ideas:**
- A pile of overdue bills labeled "code"
- A tangled ball of spaghetti wires
- A house built on a visibly shaky, cracked foundation
- A snowball of debt rolling downhill, growing bigger

---

## 17. Dependency Risk

**Word:** Dependency Risk

**Synonyms:** third-party risk, external library risk, vendor lock-in

**Description:**

Dependency risk is what happens when a project relies on something outside its own control - a third-party library, an external API, a cloud service - and that thing changes, breaks, or disappears without warning. Modern software leans heavily on other people's code and services, which is usually a huge time-saver, but it also means the project's fate is partly tied to decisions made by people who have never even heard of it.

![Broken chain link](https://images.unsplash.com/photo-1518709268805-4e9042af2176?w=600)

### Examples
- A critical npm package being deprecated, deleted, or taken over by a new maintainer
- A third-party API changing its pricing model or shutting down entirely
- A library update introducing breaking changes right before a big release
- A cloud provider having an outage that takes the whole product down with it
- Becoming so tied to one vendor's tools that switching away later is nearly impossible ("vendor lock-in")

### Consequences
- Sudden build failures or broken functionality with little warning
- Costly, time-consuming migration to alternative libraries or services
- Project delays that are completely outside the team's direct control
- Security vulnerabilities inherited from poorly maintained dependencies
- Difficult conversations with stakeholders about issues "someone else" caused

### Mitigation
Carefully vetting dependencies before adopting them, pinning specific versions rather than always using "latest," monitoring for deprecation notices, and having a contingency or fallback plan for critical third-party services.

**AI Context:** Dependency Risk = relying on external libraries, APIs, or services the team doesn't control, which can break, change pricing, or disappear unexpectedly and disrupt the project.

**Ideas:**
- A chain with one rusty, broken link in the middle
- A house of cards built on top of someone else's card
- A puppet dancing on strings held by another hand
- A single support beam holding up a whole building

---

## 18. Miscommunication

**Word:** Miscommunication

**Synonyms:** misunderstanding, unclear requirements, crossed wires

**Description:**

Miscommunication is the quiet source of a huge number of project problems - not because anyone did anything wrong on purpose, but because information got lost, garbled, or interpreted differently by the person receiving it than the person who sent it. It's especially common in teams that rely heavily on quick verbal exchanges or brief messages instead of clear, written communication.

![Two people with crossed wires between them](https://images.unsplash.com/photo-1543269865-cbf427effbad?w=600)

### Examples
- A developer building the wrong feature because a ticket was too vague
- Two teams each assuming the other one is handling a particular task
- Verbal feedback given in a meeting that's never written down or confirmed afterward
- A message read out of context and taken the wrong way
- Different team members using the same word to mean subtly different things

### Consequences
- Wasted development time and significant rework
- Frustration, tension, and lost trust between team members
- Missed requirements or duplicated effort across the team
- Decisions being made on false assumptions
- Small misunderstandings compounding into much larger problems over time

### Mitigation
Favoring clear written documentation over verbal-only communication, confirming understanding by summarizing back what was agreed, and setting up structured communication channels so nothing important gets lost in casual chat.

**AI Context:** Miscommunication = information being misunderstood, lost, or interpreted differently between people, causing wasted work, wrong assumptions, or missed requirements.

**Ideas:**
- Two tangled telephone wires crossing each other
- A game of telephone with a hilariously garbled final message
- Two speech bubbles that clearly don't match each other
- A letter arriving at completely the wrong address

---

*End of dictionary. Please review and confirm the four new entries (Scope Creep, Technical Debt, Dependency Risk, Miscommunication) before adding them to the game.*