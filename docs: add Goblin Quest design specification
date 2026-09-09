# Goblin Quest — Design Specification

## 1. Purpose

Goblin Quest is an Android-first, game-like online learning platform that turns learning into the loop:

Motivate → Learn → Practice → Challenge → Win → XP + GOBLINS → Celebrate → Repeat.

It supports school, college, university, and independent learners, with adaptive AI coaching, competitive challenges, Guilds, events, school Goblin Quests, and strong privacy and safety controls.

## 2. Product Principles

- Learning comes first; gamification reinforces learning.
- AI adapts to demonstrated performance and remembers relevant learning context.
- Level and Rating are separate.
- Level measures progression.
- Rating is a percentage representing performance.
- Private personal learning stays private unless deliberately brought into an institution or event context.
- Competition rewards learning and digital progression, not guaranteed cash prizes.
- Owner controls are powerful but do not override learner privacy or safety.

## 3. Technical Architecture

- Flutter, Android-first.
- Designed for later web and iOS expansion.
- Supabase for authentication, database, storage, and backend services.
- Secure server-side AI integration.
- AI provider secrets must never be exposed inside the mobile application.

## 4. Core Learner Experience

Users can study:

- School subjects
- Languages
- Coding
- Business
- General knowledge
- Other educational topics

Personal learning includes:

- Learn
- Practice
- AI Coach
- 1vAI challenges

Users earn XP and GOBLINS, level up, maintain streaks, and unlock digital items.

## 5. AI Memory and Adaptation

The AI Coach records relevant learning progress and mastery signals.

Difficulty adapts based on actual performance.

Users may choose a preferred learning speed:

- Fast
- Slow

The AI also adapts based on demonstrated performance rather than relying only on the user's selected speed.

1vAI is part of the learning cycle.

The AI can:

- Teach a concept.
- Practice the concept.
- Ask recall questions later.
- Detect when the learner does not understand.
- Re-teach the concept.
- Retry the learner.
- Increase or decrease difficulty.

Guild learning and 1vAI form a continuous loop:

Guild learning → 1vAI → improve → Guild learning → repeat.

## 6. Gamification

Goblin Quest uses:

- XP
- GOBLINS
- Levels
- Streaks
- Shop
- Avatars
- Outfits and accessories
- Celebration effects
- Boosts
- Event cosmetics
- Special digital items

Items may be earned through learning or purchased with in-app currency where configured.

### Level and Rating

Level and Rating are different.

Example:

Level 100  
Rating 73%

Rating is a percentage based on actual performance.

Rating can change as the learner improves.

Matchmaking uses Rating ranges so learners generally compete against others with similar performance.

## 7. Guilds

Guilds are study communities.

Guilds have:

- Members
- Guild XP
- Guild levels
- Guild upgrades
- Challenges
- Battles
- Leaderboards
- Guild Shop
- Digital rewards

Guild-vs-Guild competition should match similar learning contexts.

Examples:

English Guild vs English Guild

Maths Guild vs Maths Guild

African-language Guild vs African-language Guild

The goal is:

The more we fight, the more we learn.

## 8. Events

### Goblin Celebration

Goblin Celebration happens every Thursday from 16:00–22:00.

It should feel like a real recurring event, not simply a post-win screen.

It can include:

- Special challenges
- Rewards
- Leaderboards
- Cosmetics
- Celebration effects
- Special activities

### AI Challenge Event

Individual learners compete against adaptive AI-generated tests and challenges.

### World Arena

World Arena allows real users to compete against real users.

AI can generate and control:

- Questions
- Difficulty
- Scoring
- Tie-breakers

Ties can use additional tie-breaker questions.

Higher-performing winners can eventually face stronger opponents.

### Anti-cheat

The system may use:

- Timing
- Answer patterns
- Unusual behavior
- Other risk signals

Suspicious results can be flagged for review.

The system must not claim that it can perfectly prove AI cheating from answers alone.

### Tuesday Update Day

Tuesday can be used as Goblin Update Day.

It can announce:

- New AI features
- New challenges
- Guild features
- Shop items
- New learning content
- Upcoming changes

Subscription price changes must be announced transparently.

Prices must not silently change.

### Owner Events

The owner can create special events, including seasonal events.

Owner-created events can include:

- Dates
- Challenges
- Rewards
- Avatars
- Guild activities
- Learning content
- Event leaderboards
- Event-only digital items

## 9. Goblin Quest Institution System

Goblin Quest supports:

- Primary schools
- High schools
- Colleges
- Universities
- Independent learners

Institutions can create Goblin Quests and invite learners.

Grades 1–12 are supported.

A Quest may contain many subjects.

Each student can select a maximum of 5 subjects.

Teachers can:

1. Set exact questions themselves.

OR

2. Choose a subject, topic, and difficulty and allow AI to generate questions.

### Monthly School Quest

A school Quest runs every day and ends every month.

At the end of the monthly Quest, results can award:

- XP
- GOBLINS
- Gear
- Digital rewards
- Other configured rewards

Cash rewards are not guaranteed.

## 10. Institution Analytics and Privacy

Institutions can have dashboards showing Quest-related aggregate information such as:

- Number of enrolled students
- Participation
- Active percentage
- Popular subjects
- Popular topics
- Challenge participation
- Overall progress
- Rankings
- Other aggregate Quest statistics

Private personal learning outside a Goblin Quest remains private.

For example, if a student privately studies History outside the school's Quest, the school does not automatically receive that private learning history.

If a student participates in a school Quest or event, institution staff can see information relevant to that Quest or event.

Private AI conversations outside the institution context must not automatically become visible to schools.

## 11. Institution Pricing

The owner's own school's Goblin Quest is free.

Students in the owner's school do not individually pay.

Other schools or institutions pay for their own Goblin Quest at institution level.

Students at those institutions do not individually pay for the school Quest.

An initial pricing idea may be around R50 per grade.

Examples:

Grade 9 = R50

Grade 10 = R50

Grades 9 + 10 = R100

Grades 1–12 = R600

These amounts are not permanently locked.

Pricing must be configurable by the owner/admin rather than hard-coded.

## 12. Premium

Individual Premium provides features such as:

- AI Coaching
- Extended learning content
- Additional premium features
- Educational video access

A 7-day free Premium trial may be offered to eligible new users.

The discussed launch price is R16/month.

The price must remain configurable.

A school-wide Premium subscription can be paid by the school.

Students do not individually pay for school-wide Premium.

## 13. Educational Video System

Goblin Quest can provide original educational video lessons.

AI can create original educational video lessons based on learner needs.

The owner can upload original videos.

Third-party educational videos may only be used when properly licensed or authorized.

### Daily Video Credits

Premium users can receive a configurable number of video credits every day.

Credits:

- Refresh every day.
- Unused credits expire at the end of the day.
- Do not accumulate.
- Cannot be withdrawn as cash.
- Are used only inside the app.

The owner can configure:

- Number of daily credits.
- Which videos require credits.
- Credit costs.

## 14. Owner Control Center

The owner has administrative controls for:

- Events
- Learning content
- Video content
- Pricing configuration
- Moderation
- Platform analytics
- Shop content
- Announcements

The owner can see aggregate platform statistics such as:

- Number of users
- Active users
- Schools using the platform
- Popular learning subjects
- Popular learning topics
- Paying users
- Event statistics
- Shop performance
- Content performance
- General platform trends

The owner should not automatically see everyone's private AI conversations.

### Owner as Learner

The owner can also learn and play.

Administrative status is separate from learner progression.

Owner learner Level starts at:

Level 1

Owner Rating is based on actual performance.

The owner can continue earning XP, GOBLINS, items, and other learner rewards.

### Owner Identity

The owner's real identity remains private.

A generated public identity can be used.

Inside a particular Goblin Quest, the owner can use a context-specific identity if they join that Quest.

If the owner does not join that Quest, their identity does not change for that Quest.

## 15. World Chat and Safety

World Chat allows users to communicate globally.

Because children and teenagers may use the platform, World Chat must include:

- Reporting
- Blocking
- Moderation
- Anti-harassment controls
- Age-appropriate protections
- Safety controls
- Protection against inappropriate content

Public identities should avoid unnecessarily exposing real-world identity information.

## 16. South African Language Support

Goblin Quest should support South African languages.

Sepedi is an important supported language.

The architecture should allow additional South African languages and localization to be added later.

## 17. Security and Authorization

The system should support roles such as:

- Owner
- Administrator
- Principal
- Teacher
- Student
- Other appropriate institution roles

Server-side authorization must enforce:

- Institution boundaries
- Quest membership
- Privacy boundaries
- Administrative permissions
- User access controls

AI provider API keys and secrets must remain server-side.

## 18. Core Data Domains

The backend should eventually contain domains for:

- Users
- Profiles
- Roles
- Institutions
- Grades
- Classes
- Goblin Quests
- Quest subjects
- Student subject selections
- Learning progress
- Mastery
- AI memory/context
- Challenges
- Challenge results
- XP
- Levels
- Streaks
- GOBLINS
- Inventory
- Shop
- Items
- Guilds
- Guild memberships
- Guild battles
- Guild upgrades
- Guild Shop
- Events
- World Arena
- Matchmaking
- Leaderboards
- Institution analytics
- Subscriptions
- Billing
- Notifications
- Update announcements
- Anti-cheat risk signals
- Adjudication/review
- Privacy controls
- Video lessons
- Video credits

## 19. Delivery Strategy

### Phase 1 — MVP

Build the foundation:

- Authentication
- User profiles
- Personal Learn
- Personal Practice
- AI Coach
- 1vAI
- XP
- GOBLINS
- Levels
- Streaks
- Institution system
- Goblin Quest
- Grades
- Classes
- Maximum 5 subjects
- Teacher-created questions
- AI-generated questions
- Basic institution analytics
- Thursday Goblin Celebration
- Premium/trial configuration
- Educational video foundation
- Daily video credits foundation

### Phase 2

Add:

- Guilds
- Guild upgrades
- Guild Shop
- Guild-vs-Guild
- World Arena
- Advanced matchmaking
- Anti-cheat review
- Richer cosmetics
- Tuesday Update Center
- Full billing/admin tools

### Phase 3

Add:

- Advanced institution analytics
- More South African languages
- More localization
- Scaling and hardening
- Additional institution features
- More advanced events and learning systems

## 20. UX Direction

Goblin Quest should feel like a game while the learner is playing.

The main mobile experience should be portrait-first.

Everyday learning should remain clear and easy to use.

Challenge and battle screens should feel more game-like with:

- Large controls
- Countdown
- Score
- XP feedback
- GOBLINS feedback
- Animations
- Celebration effects
- Strong visual feedback

Goblin Celebration should feel like an actual recurring event.

## 21. Success Criteria

Goblin Quest succeeds when:

- Learners return regularly.
- Learners demonstrate measurable progress.
- AI practice adapts to learner performance.
- Learners understand their XP.
- Learners understand their GOBLINS.
- Learners understand their Level.
- Learners understand their percentage Rating.
- Learners can safely participate in social learning.
- Institutions receive useful aggregate Quest analytics.
- Private personal learning remains private outside relevant institution contexts.

## 22. Explicit Non-Goals

Goblin Quest must not:

- Promise guaranteed cash prizes.
- Silently change subscription prices.
- Claim AI can perfectly detect cheating.
- Expose private personal learning to institutions outside relevant Quest/event contexts.
- Expose AI provider secrets inside the mobile app.
- Hard-code pricing so that the owner cannot change it later.

# End of Design Specification
