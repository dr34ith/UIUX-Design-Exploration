

## Understanding Designer Roles

So I learned there are actually 6 different types of designers in the UX/UI field, which was surprising because I thought it was just "UX designer" and that's it. But it's way more specialized:

**Interaction Designers (IxD)** focus on how users actually interact with the product - like what happens when you click a button, swipe a screen, or tap an icon. They're thinking about the flow and the responses.

**Visual Designers** are what I originally thought UI designers were. They handle all the visual stuff - choosing colors, typography, spacing, making sure icons look consistent. Basically making things look good and on-brand.

**Motion Designers** are interesting - they design the animations and transitions. Like when a menu slides in or a button does that little bounce effect. I didn't realize this was a whole separate role. It's about using movement to guide users and make interactions feel smooth.

**UX Researchers** are the ones doing all the user interviews, surveys, and data analysis. They figure out what users actually need and why they behave certain ways. Seems like they spend a lot of time talking to people and analyzing patterns.

**UX Writers** write all the text in the app - button labels, error messages, tooltips, all that microcopy. The course emphasized how important clear, concise writing is for user experience. Makes sense.

**Generalists** (or "T-shaped designers") do a bit of everything. The instructor said this is super common in startups and freelancing. You're expected to know the basics of all these areas but be really good at one or two.

I'm starting to think I might lean toward being a generalist with a focus on visual design, but I need to explore more first. The course mentioned that most job postings want this T-shaped skill set anyway.

---

## The Psychology Behind Good Design

This module blew my mind. There are actual scientific principles that explain why some designs work and others don't. These aren't just guidelines - they're based on how our brains actually process information.

### Hick's Law

The basic idea: the more choices you give someone, the longer it takes them to decide.

I noticed this immediately after learning about it. Like when I'm on Netflix and there are 50 different categories showing at once - I just freeze up and can't pick anything. But when they only show like 5-7 rows, it's way easier to browse.

The instructor showed an example of a form that had everything on one page versus one that broke it into steps. The multi-step one felt way less overwhelming even though it was technically the same amount of work.

What I'm taking from this: When I'm designing, I should break complex tasks into smaller chunks. Don't show users 20 options at once if I can group them or present them in stages. Keep primary actions to 1-2 per screen.

### Miller's Law

This one says people can only hold about 7 items (plus or minus 2) in their working memory at once.

The phone number example really drove this home:

- 5550199283 is super hard to remember
- But 555-019-9283 is way easier because it's chunked into groups

So for navigation menus, I should aim for 5-7 items maximum. If there are more, I need to group them into categories. Same with any list - chunk information into digestible pieces.

### Jakob's Law

"Users spend most of their time on other sites, so they expect your site to work like all the others."

This was kind of a relief to learn because I kept thinking I needed to be super innovative with everything. But actually, using familiar patterns is GOOD. Users already know:

- The magnifying glass icon means search
- The shopping cart icon is for checkout
- The logo in the top left goes back to the home page
- The hamburger menu opens navigation

The instructor said: be innovative with your features and content, not with basic navigation and interactions. Users should spend their mental energy on YOUR content, not learning YOUR interface.

There's this quote from the course I wrote down: "Don't make users think about HOW to use your product. They should only think about WHY they want to use it."

### Fitts's Law

The time it takes to click something depends on two things: how far away it is and how big it is.

So bigger targets + closer to where the user's cursor/finger already is = faster interaction.

On mobile, this means important buttons (like "Buy Now") should be:

1. Big enough (at least 44x44 pixels minimum, but 48x48 is better)
2. In the "thumb zone" - the area your thumb naturally reaches on a phone

On desktop, I should make primary CTAs prominent and positioned along the natural flow of where users are looking or where their cursor is likely to be.

One thing I'm realizing: secondary or destructive actions (like "Delete") should be smaller and further away so users don't accidentally hit them.

### Gestalt Principles

These are all about how our eyes naturally group things together. Really useful for layout.

**Proximity** - Things that are close together look like they belong together.

So if I have a label and an input field, they should be close (like 8px apart). But unrelated sections should have way more space between them (24-32px). This creates visual grouping without needing boxes around everything.

**Similarity** - Things that look alike seem like they have the same function.

This is why all my buttons need to have the same corner radius, all my headings need the same font weight, all my icons need the same style (either all outlined or all filled). Inconsistency makes users confused about what things do.

**Common Region** - Things inside the same boundary (like a card or box) are perceived as a group.

This is why cards work so well for grouping content. The border or background color tells users "these things are related." But I need to be careful not to use boxes randomly - every container needs a purpose or it just adds visual clutter.

I tested this on myself by looking at some apps I use and it's everywhere once you notice it. Instagram groups posts in cards, Gmail uses proximity to group email metadata, Amazon uses similarity for all their product cards.

---

## User Research and Fighting My Own Biases

This section was kind of uncomfortable because it made me realize how many ways my brain tricks me during research. The instructor kept emphasizing: "You are NOT the user" and apparently that's something every designer needs to tattoo on their brain.

### The Bias Problem

**Confirmation Bias** - I'm guilty of this one already. It's when you're looking for evidence that proves your idea is right and ignoring anything that contradicts it.

The fix is to ask open-ended questions during interviews. Instead of "Do you like this feature?" (which is basically fishing for a yes), I should ask "Tell me about your experience with..." and let them talk. Their real problems will come out.

**False Consensus Effect** - Assuming other people think and behave the same way I do.

This hits hard because I catch myself doing this constantly. Just because I would organize information a certain way doesn't mean my users would. The course hammered on this: I need to test with diverse groups of people - different ages, different tech comfort levels, different backgrounds.

The example they gave was a designer who made a super minimal interface because SHE liked minimal design, but her users (older adults) found it confusing because there weren't enough visual cues. Ouch.

**Recency Bias** - Giving too much weight to the last thing you heard or the last participant you talked to.

The solution is to take detailed notes during every interview and review ALL the data together at the end. Don't trust my memory because my brain will definitely overemphasize whatever happened most recently.

**Primacy Bias** - The opposite problem: remembering the first participant too strongly.

Same solution as recency bias - document everything and analyze it all together after all sessions are complete.

**Implicit Bias** - The unconscious stereotypes we all carry about race, gender, age, etc.

This one's harder to fix because it's unconscious. The course said to be intentional about creating diverse personas and recruiting diverse test participants. Also to question my assumptions when I catch myself thinking "oh, older people won't understand this" or "young people prefer X."

Note to self: Schedule research sessions in a random order, not grouped by demographics. That way I don't accidentally compare groups in my head while I'm doing the research.

The big takeaway: My gut feelings and assumptions are probably wrong. Data and real user feedback are what matter.

---

## UI Design Standards - The Technical Stuff

This module got into the actual numbers and measurements. At first it felt overwhelming but then I realized these are basically just standards the industry agrees on, so I don't have to reinvent the wheel.

### Typography

There's a hierarchy to text sizing and it's pretty consistent across good designs:

H1 (page titles, big hero text): 32-48px H2 (section headers): 24-32px  
H3 (sub-sections): 18-24px Body text: 16px - this is standard for readability on web, never go below 12px Small text (captions, footnotes): 12-14px

**Line height** is important too. For body text, the instructor recommended 1.5x the font size. So if my text is 16px, the line height should be 24px. For headlines it can be tighter, around 1.2x. This prevents text from feeling cramped or too spaced out.

Font families: stick to 2 maximum (one for headings, one for body text). I saw some student examples that used like 5 different fonts and it looked really chaotic. Also limit weights to maybe 3 per family - Regular, Medium, Bold is usually enough.

I'm realizing now why so many professional sites look similar - they're all following these same readability standards. It's not boring, it's functional.

### Color Theory (60-30-10 Rule)

This was super helpful for understanding how to build a color palette:

- 60% should be neutral colors (backgrounds, white space) - usually grays or whites
- 30% secondary color (headers, cards, non-critical stuff) - this can be your brand color but muted
- 10% accent color (CTAs, links, important actions) - bright, high contrast, the color that draws the eye

So for example, a site might use:

- 60%: Light gray background (#F5F5F5)
- 30%: Dark blue for headers and text (#2C3E50)
- 10%: Red for buttons and links (#E74C3C)

This explains why websites don't just blast color everywhere - the accent color is powerful BECAUSE it's used sparingly.

**Contrast ratios** are non-negotiable for accessibility:

- Normal text needs 4.5:1 contrast ratio
- Large text (18pt or bigger, or 14pt bold) needs 3.0:1

The course recommended using WebAIM Contrast Checker. I've been testing this on websites I visit and SO many fail, especially light gray text on white backgrounds. Now I understand why my eyes hurt reading some sites.

Before finalizing any color scheme, I need to run every text/background combination through a contrast checker. This isn't optional.

### The 8pt Grid System

Okay this was confusing at first but now it makes so much sense.

Everything should be sized and spaced in multiples of 8: 8px, 16px, 24px, 32px, etc.

Why? Because:

1. It prevents half-pixels (0.5px makes things look blurry on screens)
2. It scales perfectly across all screen sizes
3. Developers expect it, so handoff is easier
4. It's the industry standard

My spacing scale should look like:

```
4px - really tight spacing (like icon next to text)
8px - small spacing (label to input field)
16px - medium spacing (between elements)
24px - large spacing (between sections)
32px - extra large (between major blocks)
48px and up - huge spacing (hero sections, page margins)
```

The instructor said once you start using the 8pt grid, you can't unsee it. I looked at some well-designed apps and sure enough, all the spacing follows this system.

**Column grids** are also standardized:

- Desktop: 12 columns (usually around 1440px wide)
- Tablet: 8 columns (768px)
- Mobile: 4 columns (360-375px)

Margins and gutters are typically 16-24px on mobile, larger on desktop (24-32px).

I need to set this up in Figma from the start of every project, not try to add it later. The course showed examples of designs with and without the grid and the difference in polish was obvious.

---

## Accessibility - Designing for Everyone

The course was really clear that this isn't a "nice to have" feature, it's a requirement. The instructor said "accessibility is about removing barriers" and if my design creates barriers for anyone, I'm doing it wrong.

### WCAG Standards

WCAG = Web Content Accessibility Guidelines. It's basically the bible of accessible design.

There are three levels: A, AA, and AAA. The course said to aim for AA which is the industry standard. AAA is great but sometimes not feasible for every element.

### Color Contrast (Non-Negotiable)

I already mentioned this in the color section but it's worth repeating because it's so important:

- Normal text: 4.5:1 contrast ratio minimum
- Large text (18pt or bigger, or 14pt bold): 3.0:1 minimum

I need to check this for every text element. No exceptions. Light gray on white might look trendy but if people can't read it, it's bad design.

### Touch Targets on Mobile

Buttons and tappable elements need to be at least:

- 44x44 pixels on iOS (Apple's requirement)
- 48x48 dp on Android (Google's recommendation)

The reason is simple: human fingers need space. If buttons are too small or too close together, people will mis-tap constantly.

The instructor showed an example of a form with tiny checkboxes and I realized I've definitely rage-quit apps because of this exact problem. There should also be some spacing between tappable elements (at least 8px) so fingers don't hit the wrong thing.

### Alt Text for Images

Every image that provides information needs a text description for screen readers. But decorative images should use empty alt text (alt="") so screen readers skip them.

Examples from the course:

- Information image: `alt="Bar chart showing 60% user satisfaction in Q1 2024"`
- Decorative image: `alt=""` (tells screen reader to ignore it)

I should be writing these alt descriptions thinking about someone who can't see the image at all. What information would they need?

### Keyboard Navigation

Everything that's clickable with a mouse needs to be accessible with just a keyboard. People use Tab to move through elements and Enter to activate them.

The tab order needs to be logical - top to bottom, left to right. Not jumping around randomly.

I need to test every design by unplugging my mouse and trying to navigate with just keyboard. If I get stuck or confused, it's broken.

### Don't Rely on Color Alone

This was a good point I hadn't thought about. If I write "Click the green button to continue," what happens for colorblind users?

Better: "Click the 'Continue' button (green with checkmark icon)"

Or even better: make it obvious through size, position, and text labels so color is just reinforcing the message, not carrying it alone.

The course showed a form where errors were only indicated by turning the field red. A colorblind user wouldn't see the error at all. The fix was to add an error icon and text message along with the red color.

### Testing is Critical

The instructor said to run every design through:

1. A screen reader (like NVDA or JAWS on Windows, VoiceOver on Mac/iOS)
2. Keyboard-only navigation test
3. Contrast checker
4. Zoom test (can people enlarge text without breaking the layout?)

This feels like a lot but apparently it becomes second nature once you build it into your workflow. Accessibility should be considered from the start, not tacked on at the end.

---

## The 5-Phase Design Process

This is the framework the whole course is built around. It's not always perfectly linear in real projects (there's a lot of going back and forth) but understanding each phase helps structure my thinking.

### Phase 1: Empathize

Goal: Actually understand who I'm designing for and what they need.

The course was super clear that I can't skip this. I can't just assume I know what users want. Even if I'm part of the target audience, I still need to talk to other people.

**User Personas** - These are detailed fictional characters based on research. Not just "Sarah, 28" but:

- Name and age (makes them feel real)
- Job and responsibilities
- Goals (what they're trying to accomplish)
- Frustrations (what's stopping them)
- Tech comfort level
- Quote that captures their mindset

The instructor said to create 2-3 personas for most projects. More than that and they stop being useful.

**User Stories** - Short statements that capture what a user needs and why.

Format: "As a [who], I want to [what], so that [why]"

Example from the course: "As a busy parent, I want to order groceries in under 2 minutes, so I have more time with my kids."

This format is great because it forces me to think about the WHY, not just the WHAT. The why reveals the real problem to solve.

### Phase 2: Define

Goal: Take everything I learned in Empathize and frame it as a specific problem to solve.

**Problem Statement**

Format: "[User name] is a [characteristic] who needs [need] because [insight]"

Example: "Sarah is a time-strapped marketing manager who needs simplified analytics because current tools overwhelm her with too much data."

The instructor said this should be one sentence. If I can't fit the problem into one sentence, I don't understand it well enough yet.

**Hypothesis Statement**

This is where I start thinking about solutions, but in a testable way.

Format: "If we [action], then [outcome] will happen because [reason]"

Example: "If we auto-generate weekly summaries, then Sarah will spend 50% less time creating reports because she won't have to manually pull data."

The "because" part is important - it's my assumption about why this solution will work. When I test the design, I'm also testing whether my reasoning was correct.

### Phase 3: Ideate

Goal: Generate as many possible solutions as I can. Quantity over quality at this stage.

**Crazy 8s**

This exercise is intense but effective:

1. Fold a paper into 8 sections
2. Set a timer for 8 minutes
3. Sketch one different idea in each section (1 minute each)

The point is to force myself to think fast and not overthink. The instructor said the best ideas often come from this rapid sketching because you bypass your inner critic. Some will be terrible and that's fine.

**How Might We (HMW) Questions**

This is about reframing problems as opportunities.

Instead of: "Users can't find the search feature" Ask: "How might we make search more discoverable?"

The HMW format opens up possibilities instead of focusing on what's wrong. It's a more creative mindset.

**Competitive Audit**

Look at 3-5 competitors and analyze:

- What do they do well?
- What do they do poorly?
- What's missing from the market?
- What can I learn from their mistakes?

The course emphasized: don't copy competitors, but don't ignore them either. Understanding the landscape helps me find opportunities to do something better or different.

### Phase 4: Prototype

Goal: Make the ideas from Ideation tangible so I can test them.

**User Flow**

A diagram showing the path a user takes to complete a task. Start to finish.

Example: Start → Login Screen → Home Screen → Search → Results → Product Detail → Add to Cart → Checkout → Confirmation

This helps me see the big picture and spot where users might get stuck or confused. Every arrow is a decision point or action.

**Information Architecture (IA)**

This is the structure of the site or app. Like a sitemap showing how content is organized.

The instructor recommended card sorting with users - give them cards with content topics and ask them to group them in ways that make sense. This reveals how users think about organization, which might be different from how I think about it.

**Wireframes**

Low-fidelity first: just boxes and placeholder text. The goal is to figure out layout and structure without getting distracted by colors or images. This is the fastest way to iterate because I'm not invested in making things pretty yet.

High-fidelity later: more detailed layout with real content (but still no color/branding). This is where I nail down spacing, alignment, and hierarchy.

**Mockups**

Now I add the visual design - colors, images, typography, branding. This is what the final product will actually look like.

The instructor warned: don't start with mockups. If the structure is wrong, making it pretty won't fix it. Get the bones right first.

**Prototype**

Make it clickable. Link screens together so it feels like a real app even though it's not coded yet.

Tools: Figma, Adobe XD, Framer all do this.

The course said interactive prototypes get way better feedback than static screens because users can actually experience the flow.

### Phase 5: Test

Goal: Find out what's broken before it gets built.

**Usability Study Planning**

How many participants? The course said 5-8 users will uncover about 80% of usability problems. More than 8 gives diminishing returns - you start seeing the same issues repeat.

**What to Measure (KPIs)**

- Time on Task: How long did it take to complete?
- Success Rate: Did they finish or give up?
- Error Rate: How many mistakes did they make?
- Satisfaction: Did they like using it? (Use a survey like System Usability Scale)

**Important note from the instructor: Watch users struggle and DON'T help them.** It's painful but their pain points are my design opportunities. If I jump in to explain, I'm hiding problems that need to be fixed.

**Analysis Method**

Affinity Diagram: Write each observation on a sticky note, then group similar issues together. Patterns will emerge.

Themes might be things like:

- "Navigation confusion"
- "Unclear CTAs"
- "Too many steps"
- "Text too small"

These themes become my priorities for iteration.

The course was clear: testing isn't the end. After testing comes redesign based on what I learned, then test again. It's a cycle.

---

## Building a Portfolio and Getting Work (Module 7)

This module was all about the career side. How to present work, how to get hired, how to work with clients if freelancing.

### Portfolio Case Studies

The instructor was really emphatic: recruiters care more about your PROCESS than your final pixels.

Every case study needs these sections:

**1. Project Overview** (should take like 30 seconds to read)

- My role (UX Designer, UI Designer, Researcher, etc.)
- Duration (2 weeks, 3 months, whatever)
- Tools used (Figma, Miro, Adobe XD)

**2. The Problem** (about 1 minute to read)

- What was I trying to solve?
- Who was it for?
- Why did it matter?

If I have metrics, include them here. "Users were abandoning checkout 70% of the time" is way more compelling than just "checkout was broken."

**3. The Process** (this is the meat - 3-4 minutes)

This is where I show the messy middle. The instructor said to include:

- Sketches and early ideas (even the bad ones)
- Research data and insights
- Failed iterations (what didn't work and why)
- How I made decisions

The point is to show my thinking. Anyone can show a pretty final design. Not everyone can explain WHY they made specific choices.

**4. The Solution** (about 2 minutes)

- Final designs with rationale
- Show before/after if it's a redesign
- Explain key features and how they solve the original problem

**5. The Outcome** (wrap it up in 1 minute)

- Results and impact if possible ("Reduced checkout time by 20%")
- User feedback (quotes are great)
- What I learned
- What I'd do differently next time

The instructor showed examples of portfolios that only showed final designs versus ones that showed the full process. The process-focused ones were way more impressive even when the designs weren't as polished.

Note to self: I need 3-4 really good case studies. Quality over quantity. Better to have 3 that show deep thinking than 10 surface-level ones.

### Freelance Contracts (If I Go That Route)

The course had a whole section on protecting yourself as a freelancer because apparently people get burned all the time.

**Statement of Work (SOW)**

This is basically the contract. It MUST include:

**Scope** - What I will actually do: Example: "Design 5 mobile screens (login, home, search, results, profile), 1 desktop homepage, create interactive prototype in Figma"

**Out of Scope** - What I won't do (super important): Example: "Development/coding, content writing, purchasing stock photos, unlimited revisions beyond 2 rounds"

The instructor said to be really specific about revisions. If the contract doesn't limit them, clients will ask for endless changes.

**Timeline** - Milestones with actual dates: Example:

- Week 1: Research and wireframes
- Week 2: Mockups
- Week 3: Prototype
- Week 4: Revisions and final delivery

**Payment Schedule** - When and how much:

Standard approach: 50% upfront (before starting any work), 50% on completion

For bigger projects: 33% at start, 33% at midpoint, 34% at completion

The instructor was clear: NEVER start work without getting at least some payment first. If they won't pay a deposit, they probably won't pay at the end either.

**Red flags to watch for:**

- "We'll pay you after the product launches" - this could be months or never
- "We need it in 2 days" - unrealistic timeline means problems
- "Do this for exposure/portfolio piece" - exposure doesn't pay bills

### RFP (Request for Proposal)

This is when a company asks multiple designers to bid on a project.

My proposal should include:

- My understanding of their problem
- My approach (brief overview of my process)
- Timeline estimate
- Cost estimate
- Portfolio samples of similar work

Important note from the course: Don't do detailed spec work for free. If they want me to actually design solutions as part of the proposal, that should be paid. A proposal explains HOW I would approach it, not do the actual work.

### Getting Feedback

The course talked about both giving and receiving feedback.

**Giving feedback to others:**

The old "sandwich method" (positive, negative, positive) apparently feels fake and people see through it.

Better approach: Ask questions

- "What was your goal with this layout?"
- "Tell me about this color choice"
- "How did you decide on this hierarchy?"

This makes it a conversation instead of criticism. Sometimes the designer had a good reason I didn't understand. Sometimes the questions help them realize their own issues.

When I do need to critique directly:

- Be specific. "This doesn't work" is useless.
- Better: "The CTA gets lost because it's the same size as the secondary buttons"
- Even better: "The CTA gets lost because it's the same size as the secondary buttons. What if we made it larger and a different color?"

**Receiving feedback:**

This is harder for me. The course said:

1. Listen fully before getting defensive (I definitely need to work on this)
2. Ask clarifying questions if I don't understand
3. Separate my feelings about the work from the feedback on the work
4. Thank them even if I disagree
5. Decide later what to actually act on - I don't have to implement everything

The instructor said defensiveness kills learning. If I'm explaining why my design is right instead of listening to problems, I'm not going to improve.

### Empathy (Keep Coming Back to This)

The course ended by reinforcing that empathy is the #1 skill for UX designers.

Empathy = understanding and sharing the feelings of users

It's NOT:

- Sympathy (feeling sorry for someone)
- Guessing what people want
- Designing for yourself

How to build it:

- Talk to real users, not just read reports
- Watch them use products (don't interrupt or explain)
- Ask "why" multiple times to get to root causes
- Actually try to put myself in their situation

The test: Can I explain my user's frustrations in their own words? If not, I don't have real empathy yet. I just have assumptions.

I'm realizing this is a thread through the whole course. Every phase comes back to understanding users better. That's literally the whole job.

---

## Personal Reflections and Next Steps

### Things I Need to Remember

Before I ship any design, I need to check these things (mental checklist I'm building):

**Visual stuff:**

- Am I using the 8pt grid? (Everything spaced in multiples of 8)
- Did I stick to 2 font families max?
- Did I run a contrast checker on all text? (4.5:1 minimum)
- Does my color split roughly follow 60-30-10?
- Are my components consistent? (Same corner radius, same button styles, etc.)

**Usability stuff:**

- Is the primary action obvious? (Fitts's Law)
- Do I have more than 7 navigation items? If yes, can I group them? (Miller's Law)
- Am I using standard patterns or making users learn something new? (Jakob's Law)
- Are choices overwhelming or well-organized? (Hick's Law)

**Accessibility stuff:**

- Are touch targets at least 44x44px on mobile?
- Do all informational images have alt text?
- Can I navigate everything with just a keyboard?
- Am I relying on color alone to communicate anything important?

**Content stuff:**

- Are my error messages actually helpful?
- Are button labels action-oriented? ("Add to Cart" not just "Submit")
- Did I use any jargon users might not understand?

**Testing stuff:**

- Have I tested with at least 5 users?
- Did I use real content instead of Lorem Ipsum?
- Does it work on the actual devices/browsers people will use?
- Does the prototype flow match the user journeys I mapped?

I need to make this more automatic. Right now it feels like a lot but the instructor said it becomes second nature.

### My Learning Plan

**First 2 weeks:** I'm going to focus on really internalizing those psychological laws. Maybe make flashcards for them. And I need to get comfortable with Figma - it's free and everyone seems to use it.

Also want to analyze 10 well-designed apps using the Gestalt principles. Like actually break down why they work.

**Weeks 3-4:** Practice the 8pt grid system. Maybe take 3 screens from apps I use daily and recreate them following the grid properly.

Build a color palette with proper contrast ratios using the 60-30-10 rule.

Create a typography scale and actually use it in a few practice screens.

**Weeks 5-8:** Do a real project. Not a made-up app, something solving an actual problem I've observed or experienced.

Go through all 5 phases properly - Empathize, Define, Ideate, Prototype, Test.

Document everything because this will become my first case study.

**Months 2-3:** Build my portfolio with 3 solid case studies. The instructor said quality beats quantity.

Get feedback from other designers - Reddit, Discord, Twitter, wherever I can find design communities.

Actually iterate based on feedback instead of getting defensive about it.

**Month 4 and beyond:** Start applying to jobs/projects. The course said 5 applications per week is a good target.

Keep building - maybe do the Daily UI challenge, or redesign challenges.

Share work publicly. This feels scary but apparently it's how you get noticed.

### Mindset Shifts I'm Working On

1. **Good design is invisible** - Users should accomplish their goals without thinking about the interface itself. If they're noticing the design, something's probably wrong.
    
2. **I am not the user** - This is the big one. I need to stop assuming my preferences matter. Data matters. User feedback matters. My opinions are just hypotheses to test.
    
3. **Iteration beats perfection** - Ship something, learn from it, improve it. Sitting on a design trying to make it perfect is just procrastination.
    
4. **Process over pixels** - When showing work, I need to explain my thinking and decisions, not just show pretty screens. That's what separates good designers from people who can use design tools.
    
5. **Empathy is everything** - The better I understand users, the better my designs will be. This isn't optional, it's literally the core skill.
    

### Questions I Still Have

- How do I know when to push back on stakeholder feedback versus when to listen? The course didn't really cover this.
- What do I do when users give conflicting feedback in testing?
- How much research is enough research? I don't want to get stuck in analysis paralysis.
- When is it okay to break the "rules" (like Jakob's Law)? Are there situations where innovation is worth the usability cost?

I should probably find a mentor or join a community where I can ask these questions to people with more experience.

### Final Thoughts

This course made me realize UX/UI is way more than making things look nice. It's psychology, research, testing, iteration, empathy, and communication all combined.

The technical stuff (typography, color, grids) is important but learnable. The harder part is the mindset - constantly questioning assumptions, staying curious about users, being okay with being wrong, and genuinely caring about solving problems for people.

I'm excited but also slightly overwhelmed. There's so much to learn. But I guess that's the point - if it was easy, everyone would do it.

The quote from the course I keep thinking about: "You don't need to know everything. You just need to stay curious and keep learning."

