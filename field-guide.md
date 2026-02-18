# The SHAPE Methodology Field Guide

**From Pilots That Stall to Systematic Implementation**

---

## Introduction: The Execution Gap

Most AI pilots succeed. Most scaled implementations fail.

This isn't a technology problem—it's an execution methodology problem.

Organizations everywhere face the same pattern: A team runs a successful pilot. AI generates promising results. Leadership gets excited. Then someone says "Let's roll this out company-wide."

Six months later, the initiative is quietly shelved. The pilot worked. The scaling didn't.

**The numbers tell the story:**
- 95% of AI pilots never achieve enterprise-wide deployment
- Organizations lose an average of $1.9 million per failed AI initiative
- The pilot-to-scale transition kills more AI projects than technical failure

**The problem isn't strategy.** Most organizations know what they want AI to do. They've defined goals, identified use cases, secured budget.

**The problem is execution methodology.** They lack a systematic approach to move from "this works" to "this works at scale."

### What SHAPE Provides

SHAPE is a five-phase execution methodology that bridges the gap between strategy and results:

- **S**ituation: Assess current state honestly before changing anything
- **H**ypothesis: Define measurable success criteria upfront
- **A**ction: Execute systematic pilots with clear decision frameworks
- **P**rocess: Scale what works through systematic phases
- **E**valuation: Measure continuously and iterate based on evidence

Like PAST (which provides strategic clarity), SHAPE works at every level:
- **Organizational:** Enterprise AI rollouts
- **Team:** Department-specific workflow improvements
- **Individual:** Personal productivity optimization
- **Prompt:** Iterative improvement of AI interactions

### The PAST + SHAPE Connection

**PAST tells you WHAT and WHY.** Purpose, Audience, Scope, Tone—strategic clarity about what you're trying to achieve.

**SHAPE tells you HOW and WHEN.** Systematic execution from assessment through evaluation.

Together, they form a complete system from strategy to implementation. You can use SHAPE independently, but organizations using both frameworks report the most consistent results.

### Who This Guide Is For

**Implementation leaders** who execute AI projects and need systematic methodology for scaling.

**Project managers** moving from pilot success to production deployment.

**Team leads** optimizing workflows without getting lost in tool comparisons.

**Consultants** delivering execution methodology clients can follow independently.

**Anyone** who has strategy but struggles with systematic execution.

### How to Use This Guide

Read the five SHAPE chapters sequentially to understand the methodology deeply.

Apply the worksheets to your specific implementation challenge.

Use the Takers/Shapers/Makers decision framework (Chapter 3) before every implementation.

Return to Chapter 6 for level-specific examples when needed.

---

## Chapter 1: Situation — Current State Assessment

### Why Situation Assessment Matters

Most AI implementation failures trace back to a single cause: Organizations didn't understand where they were starting from.

They assumed their data was cleaner than it was. They overestimated team readiness. They underestimated integration complexity. They didn't know that "how people actually work" differs dramatically from "how processes are documented."

**You can't plan the path without knowing the terrain.**

Situation assessment isn't bureaucratic overhead—it's the foundation that prevents expensive mistakes. The 30 minutes you spend honestly assessing current state can save months of failed implementation.

### The Self-Hosted Decision Framework

Before selecting any AI approach, assess which deployment model fits your situation.

Dr. Janna Lipenkova notes in *The Art of AI Product Development*: "For companies with the technical resources, hosting an open source model internally grants complete control over all aspects of the LM, including its fine-tuning."

But she also warns: "Data is sent to the provider's servers for processing using a managed LLM via API, which can raise privacy concerns, especially for sensitive or proprietary data."

**Infrastructure Decision Matrix:**

| Factor | API/Vendor Better | Self-Hosted Better |
|--------|-------------------|-------------------|
| Data Sensitivity | Public data, non-sensitive | Regulated, proprietary, competitive |
| Technical Team | Limited ML expertise | Can fine-tune and maintain |
| Control Requirements | Standard compliance | Audit trails, full visibility |
| Volume Economics | Variable/low usage | High-volume, predictable |
| Model Customization | General purpose sufficient | Domain-specific needed |

**Decision:** If 3+ factors favor self-hosting AND you have technical capability, evaluate build vs. buy. Otherwise, default to vendor solutions.

This adds critical infrastructure assessment to the Situation phase, preventing later scaling failures from wrong deployment model choice.

### Organizational Level Assessment

**Technology Assessment:**

What systems and tools are currently in use? Not the official IT inventory—what people actually use daily.

How well do existing systems integrate? Can data flow between them, or does someone manually copy-paste between applications?

What data is available and in what formats? Is it accessible, clean, structured? Or scattered across spreadsheets with inconsistent naming conventions?

Where are the technical skill gaps? Who on the team can troubleshoot when AI tools misbehave?

**Workflow Assessment:**

How do people actually work versus how they're supposed to work? This gap often surprises leadership. Shadow processes exist because official processes don't match reality.

Where are the biggest inefficiencies or pain points? What frustrates people most? What takes far longer than it should?

What processes are most ready for AI augmentation? Look for high-volume, repetitive tasks with clear quality standards.

Which workflows are too complex for initial AI implementation? Some processes have too many exceptions, too much tacit knowledge, too many edge cases. Save those for later.

### Shadow AI as Situation Signal

Before concluding your Situation assessment, audit shadow AI usage—the unsanctioned tools employees already use.

Dr. Janna Lipenkova observes in *The Art of AI Product Development*: "Shadow processes exist because official processes don't match reality."

**Shadow AI Audit Questions:**

- Which unofficial AI tools are employees already using?
- Why did they choose those tools over official alternatives?
- What does shadow AI adoption reveal about workflow friction?
- How can official AI solutions address what shadow AI is solving?

**The Signal:** Shadow AI isn't a security problem to eliminate—it's market research about what your users actually need. Any Situation assessment that ignores shadow AI will miss critical adoption intelligence.

When 50% of employees prefer unsanctioned tools, the problem isn't employee behavior. The problem is that official solutions don't match how work actually happens.

**Organizational Assessment:**

How comfortable are teams with new technology? Past experience predicts future adoption. Teams with successful technology adoption histories will embrace AI more readily.

Where is leadership support strongest? AI implementations need visible champions. Where are yours?

What resistance should you expect and from whom? Identify skeptics early. Their concerns often reveal real implementation risks.

### Team Level Assessment

**Before optimizing team workflows:**

What's the team's current baseline? Measure before you change. How long do tasks take now? What does quality look like today?

Where does the team spend most time? Often different from where management thinks time goes. Ask the team directly.

What frustrates the team most? These pain points reveal the highest-value implementation opportunities.

What's the team's tech comfort level? Some teams embrace new tools. Others need extensive hand-holding. Plan accordingly.

Where has the team successfully adopted tools before? Past success patterns indicate what implementation approaches will work.

### Individual Level Assessment

**For personal productivity optimization:**

Which repetitive tasks consume the most time? Track for a week. The answer often surprises you.

What's the quality standard I need to maintain? AI can accelerate low-stakes work easily. High-stakes work requires more careful implementation.

How much complexity am I comfortable managing? Be honest. Simple tools used consistently beat complex tools abandoned after a week.

What's my current workflow baseline? Measure before claiming improvement. "Feels faster" isn't evidence.

Where have I successfully changed habits before? Habit change is hard. Build on previous successes.

### Prompt Level Assessment

**For AI interaction optimization:**

What's my current process for this task? Before optimizing prompts, understand the workflow they serve.

What's working and what's frustrating? Which prompts produce usable results? Which require extensive editing?

What specific outcome do I need? Vague goals produce vague prompts produce vague outputs.

What constraints exist? Time limits, format requirements, audience expectations, compliance needs.

What have I tried before? Document failed approaches so you don't repeat them.

### Situation Assessment Tools

**AI Readiness Audit** (Rate 1-10):
- Technical infrastructure maturity
- Data quality and accessibility
- Team AI skills and comfort level
- Leadership support and budget allocation
- Change management capabilities

**Scoring:** 40-50 = Ready for aggressive implementation. 25-39 = Proceed with careful pilots. Below 25 = Foundation work needed before AI implementation.

**Workflow Mapping Exercise** (For each potential AI use case):
- Current time investment (hours/week)
- Pain point severity (1-10)
- Process standardization level (1-10)
- Data availability for AI (1-10)
- User enthusiasm for AI assistance (1-10)

**Prioritization:** Total scores indicate implementation readiness. Start with highest-scoring workflows.

---

## Chapter 2: Hypothesis — Defining Success Criteria

### Why Hypothesis Definition Matters

Most AI projects fail because success isn't clearly defined upfront.

Without clear success criteria, you can't measure results. Without measurable results, you can't make scaling decisions. Without scaling decisions, pilots drift indefinitely.

"We want to improve efficiency" isn't a hypothesis. "AI-assisted research will reduce report preparation time from 8 hours to 3 hours" is a hypothesis. One can be measured. The other can be debated forever.

**Specific hypotheses enable learning and iteration.** When you know exactly what success looks like, you can tell whether you've achieved it—and if not, why not.

### Creating Quantitative Hypotheses

**Organizational Level:**

"AI-assisted research will reduce report preparation time from 8 hours to 3 hours."

"Automated customer classification will improve sales team efficiency by 25%."

"AI content generation will increase marketing output by 50% with maintained quality scores."

"Loan processing time will decrease from 5 days to 2 days while maintaining approval accuracy."

**Team Level:**

"The team will complete weekly reporting in 30 minutes versus current 2 hours."

"Meeting notes will capture 100% of action items versus current 70%."

"Customer inquiry response time will drop from 4 hours to 30 minutes."

"First-pass document review will take 15 minutes instead of 45 minutes."

**Individual Level:**

"This automation will save 2 hours per week with less than 30 minutes setup."

"Email processing time will drop from 90 minutes to 30 minutes daily."

"Research summaries will take 15 minutes versus current 45 minutes."

"I'll complete this recurring task in half the time within two weeks."

**Prompt Level:**

"This prompt will generate usable first drafts 80% of the time."

"AI output will require less than 5 minutes of editing for typical use."

"Response quality will be consistent across similar requests."

"I'll save 60% of time on this recurring task."

### Creating Qualitative Hypotheses

Quantitative metrics matter, but qualitative outcomes often determine long-term success.

**Organizational Level:**

"Teams will find AI tools intuitive and helpful rather than frustrating."

"AI recommendations will be trusted and acted upon by experienced staff."

"AI integration will enhance rather than replace human expertise."

"Staff will view AI as augmentation, not threat."

**Team Level:**

"Team morale will improve with reduced manual work."

"Collaboration will increase with shared AI tools."

"Job satisfaction will rise as team members spend more time on strategic work."

"Inter-team coordination will improve with standardized AI outputs."

**Individual Level:**

"I'll feel more confident in my outputs."

"My work-life balance will improve."

"I'll have more time for creative and strategic thinking."

"I'll be less frustrated by repetitive tasks."

### Success Metrics Framework

**Efficiency Metrics:**
- Time savings on specific tasks
- Throughput improvements
- Resource allocation optimization
- Cost per unit of output

**Quality Metrics:**
- Accuracy improvements
- Consistency enhancements
- Error reduction rates
- Quality score maintenance or improvement

**Adoption Metrics:**
- User engagement rates
- Feature utilization levels
- User satisfaction scores
- Return usage rates (do people keep using it?)

**Business Impact Metrics:**
- Revenue impact
- Cost savings
- Customer satisfaction improvements
- Competitive positioning changes

### The Metric Readiness Gate

Veljko Krunic puts it directly in *Succeeding with AI*: "The business metric must be defined for every single AI project. AI methods are, by their nature, quantitative. The inability to easily recognize business metrics by which an AI project should be measured raises a big red flag. If you can't quantify the business result you're hoping to achieve, you have to ask yourself and your stakeholders whether the project is worth doing."

A valid hypothesis MUST include all five elements:

| Element | Valid Example | Invalid Example |
|---------|---------------|-----------------|
| Named metric | "Response time" | "Efficiency" |
| Baseline number | "Currently 4 hours" | "Currently slow" |
| Target number | "Target 30 minutes" | "Target faster" |
| Timeline | "Within 90 days" | "Soon" |
| Kill criteria | "Abandon if >60 min" | "Review if not working" |

**Gate Rule:** No hypothesis moves to Action phase without all five elements quantified. "Improve efficiency" isn't a hypothesis—it's a wish.

### The ROI Reality Check

Before finalizing your Hypothesis, verify that your ROI assumptions aren't optimistic fantasy:

| Question | Red Flag |
|----------|----------|
| Is the baseline measurement accurate? | Estimated, not measured |
| Are time savings realistic? | Based on vendor claims, not pilot data |
| Does improvement justify investment? | Marginal gains with significant cost |
| Can we actually measure the metric? | Requires new instrumentation |
| Will users report honestly? | Self-reported time savings |

If more than two red flags appear, pause. Gather real baseline data before proceeding. Over-optimistic hypotheses guarantee "failure" when reality is measured—even when actual results are positive.

### The Hypothesis Testing Mindset

Every AI implementation is an experiment. Approach it scientifically:

**State your hypothesis clearly.** If you can't write it in one sentence, you don't understand what you're testing.

**Define measurement methodology.** How exactly will you know if the hypothesis is true or false?

**Set decision criteria.** At what point will you conclude success or failure? What threshold triggers scaling versus abandonment?

**Establish timeline.** When will you evaluate results? Commit to a date.

---

## Chapter 3: Action — Systematic Pilot Execution

### The Critical First Decision: Takers vs. Shapers vs. Makers

Before any implementation, you face a fundamental choice. Research shows dramatically different success rates based on approach:

**Takers: 67% Success Rate**

Use off-the-shelf vendor solutions with minimal customization.

*Characteristics:*
- Fastest time-to-value (4-8 weeks typically)
- Lowest technical risk
- Vendor handles updates and maintenance
- Limited differentiation from competitors

*Best for:* Standard business processes, proven use cases, resource-constrained organizations, organizations new to AI.

*Example:* Implementing ChatGPT Enterprise, Microsoft Copilot, or Salesforce Einstein with standard configurations.

**Shapers: 45% Success Rate**

Customize vendor solutions for specific needs.

*Characteristics:*
- Moderate implementation timeline (8-16 weeks)
- Medium technical and organizational risk
- Some internal capability required
- Moderate differentiation possible

*Best for:* Industry-specific requirements, unique workflows, organizations with technical capability, moderate customization needs.

*Example:* Configuring Salesforce Einstein with custom data models, building on vendor APIs with specific business logic.

**Makers: 33% Success Rate**

Build custom AI solutions from scratch.

*Characteristics:*
- Longest implementation timeline (16+ weeks)
- Highest technical and organizational risk
- Significant internal capability required
- Maximum differentiation potential

*Best for:* Competitive differentiation requirements, highly unique processes, organizations with strong AI/ML capabilities.

*Example:* Developing proprietary machine learning models for specialized prediction or recommendation tasks.

### The Capability Trap Connection

**Simple tools that work reliably outperform complex customizations requiring constant maintenance.**

Organizations fall into the capability trap when they choose Shapers or Makers approaches for problems Takers solutions could solve. They're seduced by customization potential rather than guided by actual business requirements.

**50% of employees prefer unsanctioned simple tools over complex official solutions.** When your official AI tool is harder to use than ChatGPT, employees will use ChatGPT. Shadow AI exists because approved solutions are too complex.

### Decision Matrix

| Criteria | Takers | Shapers | Makers |
|----------|--------|---------|--------|
| Success Rate | 67% | 45% | 33% |
| Time to Value | 4-8 weeks | 8-16 weeks | 16+ weeks |
| Resource Needs | Low | Medium | High |
| Technical Risk | Low | Medium | High |
| Customization | Minimal | Moderate | Maximum |
| Maintenance | Vendor | Shared | Internal |
| Differentiation | Low | Medium | High |

**Default to Takers unless you have compelling, documented reasons for Shapers or Makers.**

### The Hidden Costs of Customization

The success rate differences (67% vs. 45% vs. 33%) reflect more than technical complexity. They reflect adoption friction that compounds over time.

Dr. Janna Lipenkova notes in *The Art of AI Product Development*: "To minimize adoption barriers, ensure the interface is easy to use and accessible for your team."

**Adoption Friction by Approach:**

| Approach | Typical Training | User Friction | Support Load |
|----------|------------------|---------------|--------------|
| Takers | 1-2 hours | Low (familiar interfaces) | Vendor handles |
| Shapers | 1-2 days | Medium (custom elements) | Shared responsibility |
| Makers | 1+ week | High (entirely new systems) | Internal only |

**The Hidden Cost:** Custom solutions don't just have higher failure rates—they have higher ongoing support costs, longer training cycles, and greater resistance to adoption. Every hour of training is an hour of resistance, confusion, and "I'll just do it the old way."

When a Takers solution breaks, the vendor fixes it. When a Makers solution breaks, your team fixes it—and your team has other work to do.

Veljko Krunic advises in *Succeeding with AI*: "Don't start by chasing difficult projects that tie up all your resources and destroy you if they fail. Start instead with simple projects that have big business impact."

### Pilot Selection Criteria

**High Impact, Low Complexity:** Choose use cases that deliver meaningful value without requiring extensive integration. The goal is demonstrable success, not technical achievement.

**Willing Participants:** Work with enthusiastic early adopters who will provide honest feedback. Skeptics can join Phase 2.

**Measurable Outcomes:** Select pilots where success can be clearly measured and communicated. Vague benefits can't build organizational momentum.

**Representative Challenges:** Ensure pilots address real organizational needs, not just interesting technical possibilities. Toy problems don't prove anything.

**Favor Takers Approach:** Unless you have compelling reasons for customization, start with proven vendor solutions. You can always customize later.

### Pilot Execution Framework

**Week 1-2: Setup and Training**
- Tool configuration (minimal for Takers, extensive for Makers)
- User training and support materials creation
- Baseline metrics measurement (before AI implementation)
- Communication plan with broader organization
- Support escalation paths defined

**Week 3-8: Active Pilot**
- Daily usage monitoring and support availability
- Weekly feedback collection from all pilot users
- Iterative improvements based on user input
- Documentation of unexpected challenges and benefits
- Regular check-ins with pilot team

**Week 9-10: Evaluation and Documentation**
- Comprehensive success metrics analysis versus hypotheses
- User satisfaction assessment
- Cost-benefit calculation
- Technical performance review
- Scaling recommendations and requirements documentation

### The Communication Protocol

Most AI projects fail before implementation begins—in the pitch meeting. Technical teams present AI in technical terms. Executives need business terms. The gap between those languages is where initiatives die.

Dr. Janna Lipenkova emphasizes in *The Art of AI Product Development* that effective AI communication must be "precise, business focused, and free of unnecessary technical jargon."

**Pilot Communication Protocol:**

| Audience | Communication Focus | Avoid |
|----------|---------------------|-------|
| Executive sponsors | Business outcome progress | Technical metrics |
| Pilot users | Daily workflow impact | Roadmap promises |
| IT/Security | Stability and compliance | Performance benchmarks |
| Skeptics | Honest challenges + solutions | Overselling results |

**Weekly Pilot Updates Must:**
1. Lead with business outcome progress, not technical status
2. Include honest challenges (builds trust faster than false optimism)
3. Avoid jargon that creates distance between teams
4. Show user perspective, not project perspective

The same project needs different translations for different audiences. What resonates with your CFO will confuse your pilot users. What excites your IT team will bore your executive sponsor.

### Team-Level Pilot Example

**Team:** Customer support optimizing response workflows

**Situation:** 4-hour average response time, inconsistent quality, team burnout from repetitive questions.

**Hypothesis:** AI-powered response suggestions can reduce average response time to 30 minutes while improving consistency and reducing team stress.

**Action:** 2-week pilot with 3 team members. Test different AI assistance levels—from simple templates to full draft generation.

**Takers Approach:** Use existing helpdesk platform's AI features rather than building custom solution.

**Success Criteria:** >50% time savings, quality maintained (measured by customer satisfaction scores), team satisfaction improved (measured by weekly pulse survey).

### Individual-Level Pilot Example

**Individual:** Consultant spending 10 hours/week on client reporting.

**Situation:** Manual reporting across 5 clients, inconsistent formats, time-consuming data gathering and synthesis.

**Hypothesis:** AI-assisted reporting can reduce time from 10 hours to 2 hours while maintaining personalization and quality.

**Action:** Create reporting templates for each client type. Test AI assistance for data synthesis, formatting, and first-draft generation over 3 weeks.

**Process:** Refine templates based on client feedback. Standardize workflow for maximum efficiency.

**Evaluation:** Track time savings weekly. Assess client satisfaction monthly. Iterate quarterly.

### Prompt-Level Pilot Example

**Task:** Optimizing executive summary generation.

**Situation:** Current prompts produce inconsistent quality—sometimes too technical, sometimes too vague, often missing key points.

**Hypothesis:** A refined prompt with clear PAST elements will deliver usable summaries 90% of the time with less than 5 minutes editing.

**Action:** Test 3 different prompt variations over 15 summary generations. Document which produces best results against quality checklist.

**Process:** Once best approach identified, create template and refine based on actual ongoing usage.

**Evaluation:** After 30 uses, assess consistency, editing time required, and areas for improvement.

---

## Chapter 4: Process — Systematic Scaling Methodology

### Why Pilots Succeed and Scaling Fails

Pilots get special attention. Selected users. Close support. Rapid iteration. High visibility.

Scaling gets none of that. Broader user base. Stretched support. Slow iteration. Reduced visibility.

**Successful pilots must be systematically scaled, not just copied.**

The same implementation that worked with 5 enthusiastic users in one department will fail with 50 skeptical users across the organization—unless you systematically adapt your approach.

### Scaling Readiness Assessment

Before scaling, honestly assess readiness across three dimensions:

**Technical Readiness:**
- Can infrastructure support broader usage without performance degradation?
- Are integrations stable and secure at scale?
- Is support documentation comprehensive enough for self-service?
- Are troubleshooting playbooks developed from pilot learnings?

**Organizational Readiness:**
- Are change management processes in place?
- Is additional training capacity available?
- Are success stories compelling and well-documented for skeptics?
- Do pilot users want to champion broader adoption?

**Resource Readiness:**
- Is budget allocated for expanded implementation?
- Are internal champions identified and empowered?
- Are vendor relationships and contracts scalable?
- Is ongoing support staffed adequately?

### The Adoption Readiness Gate

Dr. Janna Lipenkova emphasizes in *The Art of AI Product Development*: "AI's value isn't realized until it's successfully integrated into real-world workflows and embraced by users."

Technical readiness isn't enough. Before scaling, pass this adoption readiness gate:

**Pre-Scaling Adoption Check:**

| Factor | Question | Ready If... |
|--------|----------|-------------|
| Workflow Integration | How many steps change for new users? | ≤3 steps change |
| Interface Accessibility | Can non-technical staff use independently? | No IT support required |
| Training Load | How long until productive? | <4 hours training |
| Fallback Plan | What happens when AI fails? | Documented manual process exists |
| User Advocacy | Do pilot users want to champion expansion? | Active advocacy present |
| Support Scalability | Can support handle 5x users? | Yes without linear headcount |

**Scoring:** All factors "ready" = proceed with scaling. Any factor "not ready" = address before scaling.

This gate prevents the common failure pattern: technically ready but adoption-doomed scaling attempts. A system that works perfectly but nobody uses delivers zero value.

### The Simplicity Principle

**Remember the shadow AI lesson:** 50% of employees prefer unsanctioned simple tools over complex official solutions.

When scaling, resist the temptation to add complexity. The pilot succeeded partly because it was simple. Every additional feature, integration, and approval layer reduces success probability.

**The Customization Trap:**

Someone will request customization during scaling. "Can we add integration with System X?" "Can we build a custom dashboard?" "Can we modify the workflow for our specific needs?"

These requests seem reasonable. They often kill scaling initiatives.

**67% of Takers implementations succeed versus 33% of Makers.** The difference is simplicity. Every custom layer reduces success probability.

**Ask before approving customization:**
- Does this customization deliver measurable business value that justifies the added complexity?
- Would users actually prefer the complex version to the simple version?
- Does this move us from Takers toward Shapers or Makers territory?
- Can we achieve 80% of the benefit without this complexity?

### The Complexity Creep Audit

Schedule this monthly during scaling. Complexity creeps in one "reasonable" request at a time.

**Monthly Complexity Check:**

| Question | Red Flag |
|----------|----------|
| Are we adding features users didn't request? | Yes |
| Is training time increasing? | By >20% |
| Are support tickets increasing per user? | Yes |
| Would shadow AI tools still be simpler? | Yes |
| Are customization requests driving scope? | Yes |
| Is the pilot version now "legacy"? | Yes |

**The Rule:** If 3+ red flags appear, pause scaling and simplify. Every month that passes without this check, the system becomes harder to simplify.

The best implementations look almost identical at month 12 as they did at month 1—because the team resisted complexity at every decision point.

### Systematic Scaling Phases

**Phase 1: Adjacent Expansion**

Expand to similar use cases within the same department. Add users with similar skill levels and responsibilities.

*During Phase 1:*
- Maintain close monitoring and support
- Keep support ratios high (more support per user than at scale)
- Document all issues and solutions
- **Keep it simple:** Resist customization requests until Phase 2 is complete

*Phase 1 Success Criteria:*
- Adoption metrics maintained from pilot
- Minimal new issue types (problems should be familiar from pilot)
- Users can self-serve for common issues
- Support load is manageable

**Phase 2: Cross-Functional Integration**

Connect AI workflows across departments. This is where organizational complexity enters.

*During Phase 2:*
- Develop cross-functional success metrics
- Build organizational AI governance processes
- Create integration points between department workflows
- **Selective complexity:** Add integrations only when business value clearly justifies complexity

*Phase 2 Success Criteria:*
- Cross-functional workflows demonstrating value
- Governance processes preventing shadow AI growth
- Support scalable without linear headcount increase
- Integration points stable and documented

**Phase 3: Strategic Integration**

Integrate AI capabilities with core business processes. This is where competitive advantage emerges—or where over-engineering destroys value.

*During Phase 3:*
- Integrate AI with core business processes
- Develop AI-enhanced competitive advantages
- Build organizational AI capabilities and culture
- **Strategic customization:** Custom development only for genuine competitive differentiation

*Phase 3 Success Criteria:*
- Measurable competitive advantage from AI capabilities
- AI embedded in core business processes
- Organization has AI capability as strategic asset
- Innovation pipeline producing new AI applications

### Team-Level Scaling

**From pilot team to adjacent teams:**
- Document what worked and why
- Identify early adopter champions in adjacent teams
- Adapt training materials for different contexts
- Maintain simplicity—resist "improvements" that add complexity

**From pilot users to full team:**
- Phase rollout within team (don't flip the switch for everyone at once)
- Pair pilot veterans with new users
- Create feedback channels for continuous improvement
- Monitor adoption metrics weekly

**From single workflow to multiple workflows:**
- Apply SHAPE methodology to each new workflow
- Resist temptation to build one complex system for all workflows
- Simple tools for each workflow beat complex unified platforms

### Individual-Level Scaling

**From one workflow to similar workflows:**
- Apply same prompt patterns to analogous tasks
- Create personal template library
- Iterate based on what actually works versus what should work

**From occasional use to daily habit:**
- Build AI into existing routines (don't create new routines)
- Remove friction from AI access
- Make AI the default, with manual as fallback

**From single tool to integrated toolkit:**
- Add tools slowly—master one before adding another
- Integrate tools that work together naturally
- Abandon tools that don't deliver consistent value

---

## Chapter 5: Evaluation — Continuous Improvement Framework

### Why Evaluation Never Stops

AI implementation is not a project—it's an ongoing capability development process.

Technology evolves monthly. New tools emerge. User needs change. Competitive landscape shifts. What worked yesterday may not work tomorrow.

**Continuous evaluation enables:**
- Early detection of degrading performance
- Identification of new opportunities
- Evidence-based scaling decisions
- Organizational learning and capability building

### Monthly Evaluation Cycles

**Quantitative Performance Review:**
- Success metrics trending analysis (are we still meeting hypotheses?)
- Cost-benefit ratio assessment (is ROI improving or declining?)
- User adoption rate monitoring (growing, stable, or declining?)
- Technical performance optimization (speed, reliability, accuracy)

**Qualitative Impact Assessment:**
- User satisfaction and feedback analysis (what do users actually say?)
- Organizational culture impact evaluation (how is AI changing how people work?)
- Unexpected benefits and challenges documentation (what surprised us?)
- Strategic value realization progress (are we achieving intended outcomes?)

**Simplicity Check:**
- Are we adding unnecessary complexity?
- Could we achieve similar results with simpler approaches?
- Are custom features actually being used?
- Would shadow AI users prefer our solution to unsanctioned alternatives?

### Quarterly Strategic Reviews

**Capability Assessment:**
- What new AI capabilities have been developed?
- How has organizational AI maturity progressed?
- What new opportunities have emerged from our learnings?

**Competitive Analysis:**
- How do our AI capabilities compare to competitors?
- What new competitive advantages have been created?
- Where are we falling behind industry leaders?

**Strategic Alignment Review:**
- How well do current AI implementations support business strategy?
- What adjustments are needed based on market changes?
- What new AI investments should be prioritized?

**Build vs. Buy Re-evaluation:**
- Are our custom solutions still delivering differentiated value?
- Could vendor solutions now address our needs more effectively?
- Should we simplify by migrating custom builds to vendor platforms?
- Has the Takers/Shapers/Makers balance shifted since last review?

### The Build vs. Buy Re-evaluation Framework

Organizations often maintain custom solutions past their strategic value due to sunk cost bias. Every quarterly review should explicitly assess whether custom implementations still justify their complexity.

**Quarterly Build vs. Buy Reassessment:**

| Question | Action if Yes |
|----------|---------------|
| Are we maintaining custom code that vendors now offer? | Evaluate migration to vendor solution |
| Is our custom solution now commodity capability? | Consider standardization |
| Has vendor ecosystem improved significantly? | Reassess approach (Makers → Shapers → Takers) |
| Are maintenance costs exceeding value delivered? | Simplify or sunset |
| Could we redirect engineering to differentiated work? | Evaluate shift in resource allocation |

**The Sunk Cost Trap:** "We've already invested so much" is not a valid reason to continue. The question is always: "Given where we are now, what's the best path forward?"

What was differentiated custom work two years ago may now be commodity capability that vendors do better, cheaper, and with less maintenance burden.

### Team-Level Evaluation

**Weekly:** Quick metrics check, user satisfaction pulse. Are we still on track?

**Monthly:** Comprehensive workflow analysis, efficiency gains measurement, team feedback synthesis.

**Quarterly:** Team capability assessment, strategic alignment review, next quarter planning.

### Individual-Level Evaluation

**Daily:** Quick reflection—what worked, what didn't, what to try tomorrow.

**Weekly:** Time savings analysis, quality assessment, habit formation check.

**Monthly:** Workflow optimization review, skill development assessment, tool utilization audit.

**Quarterly:** Major iteration decision—continue, modify, or abandon current approaches.

### Prompt-Level Evaluation

**After 5 uses:** Does this prompt consistently deliver acceptable results?

**After 10 uses:** Should I refine or replace this prompt?

**After 20 uses:** Is this prompt optimized, or does it need significant overhaul?

**After 50 uses:** Time for complete review. Technology may have changed. Use case may have evolved. Start SHAPE cycle again.

### Evaluation-Driven Decisions

Evaluation should drive clear decisions:

**Continue:** Metrics meeting or exceeding hypotheses. User satisfaction high. No simplification opportunities.

**Expand:** Strong performance with clear adjacent opportunities. Scaling readiness confirmed.

**Modify:** Performance acceptable but improvable. Specific changes identified. Resources available for iteration.

**Simplify:** Performance acceptable but complexity higher than necessary. Opportunity to reduce without losing value.

**Pause:** Performance declining or stagnant. Investigation needed. Don't scale while diagnosing problems.

**Abandon:** Hypotheses clearly false. Cost-benefit negative. Resources better deployed elsewhere.

---

## Chapter 6: SHAPE Application Examples Across Levels

### Organizational Implementation Example

**Organization:** Regional bank implementing AI for loan processing and customer service

**Full SHAPE Application:**

**Situation Assessment:**
- Legacy systems with limited integration capabilities
- Highly regulated environment requiring extensive compliance
- Experienced staff skeptical of automation
- Strong data security requirements
- Technical infrastructure: 6/10
- Data quality: 5/10
- Team readiness: 4/10
- Leadership support: 8/10

**Critical Decision: Takers Approach**
- Regulatory environment demands proven, compliant solutions
- Staff skepticism suggests need for low-risk initial implementation
- Leadership support means opportunity to build confidence systematically
- Select established vendor with industry compliance features rather than custom build

**Hypothesis Definition:**
- "AI pre-screening will reduce loan processing time by 30% while maintaining approval accuracy above 98%"
- "Automated customer inquiries will improve response time by 50% without reducing satisfaction scores"
- "Staff will embrace AI tools that enhance rather than replace their expertise" (measured by adoption rates and satisfaction surveys)

**Action (Pilot Program):**
- Selected: Commercial loan pre-screening for pilot (high volume, clear metrics, willing team)
- 8-week pilot with weekly feedback sessions
- 12 enthusiastic early adopters from lending team
- Clear baseline metrics established before implementation
- Vendor support engaged for training and troubleshooting

**Results from Action Phase:**
- Processing time reduced 35% (exceeded hypothesis)
- Accuracy maintained at 99.2% (exceeded hypothesis)
- 10 of 12 pilot users rated experience "positive" or "very positive"
- Three unexpected benefits identified: better documentation, fewer manual errors, improved audit trail

**Process (Scaling):**
- Phase 1: Expand to full lending team (45 users) over 6 weeks
- Phase 2: Add retail loan pre-screening (similar workflow, different product)
- Phase 3: Customer service inquiry routing
- Simplicity principle: Resisted 4 customization requests that would have added complexity without clear ROI

**Evaluation Results:**
- 6-month review: 87% daily usage rate across expanded user base
- Customer satisfaction maintained (no decline from pre-AI baseline)
- Staff satisfaction improved (less time on routine tasks)
- ROI: 340% return on implementation investment
- Decision: Proceed with Phase 3 customer service implementation

### Team Workflow Example

**Team:** Marketing team optimizing content production workflow

**SHAPE Application:**

**Situation:**
- 6-person team producing 20 pieces of content monthly
- Average production time: 8 hours per piece
- Quality inconsistent—some content excellent, some mediocre
- Team spending excessive time on research and first drafts
- High burnout from repetitive writing tasks

**Hypothesis:**
- "AI-assisted content production will reduce average production time from 8 hours to 4 hours per piece"
- "Content quality scores will remain at or above current average"
- "Team satisfaction will improve as repetitive work decreases"

**Action:**
- 4-week pilot with 2 team members
- Test AI for: research synthesis, first draft generation, headline variations
- Takers approach: Use existing content platform AI features rather than custom prompts
- Success metrics: time per piece, quality scores from review process, team pulse surveys

**Process:**
- Week 1-2: Setup, training, baseline measurement
- Week 3-6: Active pilot with daily logging
- Week 7-8: Evaluation and scaling decision

**Results:**
- Production time reduced to 5.5 hours average (31% improvement, below 50% hypothesis)
- Quality scores improved slightly (unexpected positive)
- Team satisfaction significantly improved ("I finally have time for strategy")

**Scaling Decision:** Scale to full team with modified hypothesis (35% improvement realistic, 50% aspirational). Address quality variance through standardized review process.

### Individual Productivity Example

**Individual:** Consultant managing multiple client relationships and deliverables

**SHAPE Application:**

**Situation:**
- 8 active clients with different communication styles and requirements
- 12 hours weekly spent on client reporting and updates
- Quality inconsistent due to time pressure
- High cognitive load tracking different client contexts

**Hypothesis:**
- "AI-assisted client management will reduce reporting time from 12 hours to 4 hours weekly"
- "Client satisfaction will remain stable or improve"
- "Cognitive load will decrease (measured by end-of-week energy levels)"

**Action:**
- 3-week pilot across 3 representative clients
- AI applications: meeting note synthesis, progress report generation, email drafting
- Document what works and what doesn't for each client type

**Process:**
- Week 1: Establish baseline, test initial approaches
- Week 2: Refine based on what works
- Week 3: Standardize successful approaches

**Results:**
- Reporting time reduced to 5 hours weekly (58% improvement)
- Two clients commented positively on "improved communication"
- Cognitive load decreased (Friday energy significantly better)

**Scaling:** Roll out to remaining 5 clients over 2 weeks. Create client-specific templates based on pilot learnings.

### Prompt Optimization Example

**Task:** Weekly executive briefing generation

**SHAPE Application:**

**Situation:**
- Current process: 45 minutes gathering information, 30 minutes writing, 15 minutes formatting
- Quality inconsistent—sometimes too detailed, sometimes missing key points
- Executive feedback: "Usually helpful, occasionally misses what I actually need to know"

**Hypothesis:**
- "A refined prompt structure will produce usable first drafts in 80%+ of weekly briefings"
- "Total preparation time will decrease from 90 minutes to 30 minutes"
- "Executive satisfaction will improve ('always helpful' feedback)"

**Action:**
- Test 3 prompt variations over 6 weeks (2 weeks each)
- Variation A: Simple structure (situation, key developments, decisions needed)
- Variation B: PAST-structured (purpose, audience, scope, tone specified in prompt)
- Variation C: Example-based (include previous successful briefing as template)

**Results:**
- Variation A: 60% usable (too generic)
- Variation B: 85% usable (consistent quality)
- Variation C: 75% usable (over-fitted to example)

**Process:**
- Standardize on Variation B structure
- Create template with customization points for different meeting contexts
- Add checklist for critical items that must be included

**Evaluation:**
- After 10 weeks: 90% usable first drafts
- Total time: 25 minutes average (72% improvement)
- Executive feedback: "Much better—you always know what I need to know"

---

## Conclusion: From Pilots to Systematic Advantage

### Why SHAPE Works

**Simple enough to remember.** Five phases, five letters. You can recall it in any meeting, any situation.

**Comprehensive enough to prevent major failures.** Each phase addresses a common failure mode. Situation prevents bad assumptions. Hypothesis prevents unmeasurable goals. Action prevents analysis paralysis. Process prevents scaling disasters. Evaluation prevents stagnation.

**Flexible enough to apply at any level.** The same methodology that guides enterprise implementations guides individual prompt optimization. The logic scales because execution patterns are consistent.

**Systematic enough to ensure consistency.** Following SHAPE means following the same approach every time. Consistency enables organizational learning. Learning enables improvement.

### The SHAPE + PAST Power Combination

**PAST gives you strategic clarity:** What are you trying to achieve (Purpose)? Who does it serve (Audience)? What are the boundaries (Scope)? How should it feel (Tone)?

**SHAPE gives you execution methodology:** Where are you now (Situation)? What does success look like (Hypothesis)? How will you test (Action)? How will you scale (Process)? How will you improve (Evaluation)?

**Together:** Complete system from "why are we doing this?" to "did it work and what's next?"

### The Critical Numbers to Remember

**67% vs. 33%:** Takers implementations succeed at twice the rate of Makers. Simplicity wins.

**50%:** Half of employees prefer unsanctioned simple tools. Complexity kills adoption.

**95%:** Most AI pilots never scale. Systematic methodology prevents this.

### Your Next Steps

**If you have a specific implementation challenge:**
1. Start with Situation assessment—30 minutes of honest evaluation
2. Write your Hypothesis in one sentence with measurable criteria
3. Choose your approach: Takers, Shapers, or Makers (default to Takers)
4. Design a minimal pilot with clear timeline and success criteria
5. Document everything for the Process phase

**If you need strategic clarity first:**
Start with the PAST Framework Guide to establish Purpose, Audience, Scope, and Tone before applying SHAPE for execution.

**If you're ready for comprehensive implementation:**
The Strategic Frameworks Bundle (PAST + SHAPE) provides complete methodology from strategy through evaluation.

### Remember

Pilots succeed. Scaling fails—unless you have systematic methodology.

Simplicity scales better than complexity.

Takers approach (67% success) beats Makers (33%).

SHAPE works because execution patterns are consistent across levels.

Whether implementing enterprise AI or optimizing prompts, follow the same discipline: Situation, Hypothesis, Action, Process, Evaluation.

**The question isn't whether AI can help you. The question is whether you'll implement it systematically enough to actually realize that help.**

SHAPE is your answer.

---

## Worksheets & Templates

### SHAPE Methodology Worksheet

*Use this worksheet for any implementation initiative—organizational, team, individual, or prompt level.*

**Implementation Name:** ________________________________

**Level:** [ ] Organizational [ ] Team [ ] Individual [ ] Prompt

**Date Started:** _____________

---

**SITUATION ASSESSMENT**

Current state description:

_______________________________________________________________

Key pain points (list top 3):

1. ____________________________________________________________

2. ____________________________________________________________

3. ____________________________________________________________

Readiness Scores (1-10):

- Technical readiness: ___
- Data quality: ___
- Team/user readiness: ___
- Leadership/personal support: ___
- Change capacity: ___

**Total Score:** ___ /50

Baseline metrics to track:

_______________________________________________________________

---

**HYPOTHESIS DEFINITION**

Quantitative success hypothesis:

"_____________________________________________________________"

Qualitative success hypothesis:

"_____________________________________________________________"

Timeline for evaluation: _____________

Decision criteria (what number/outcome triggers scaling vs. abandonment?):

_______________________________________________________________

---

**ACTION PLANNING**

Implementation approach: [ ] Takers (67%) [ ] Shapers (45%) [ ] Makers (33%)

Justification for approach choice:

_______________________________________________________________

Pilot scope (users, duration, use case):

_______________________________________________________________

Pilot success criteria:

_______________________________________________________________

Key risks and mitigation:

_______________________________________________________________

---

**PROCESS PLANNING**

Phase 1 (Adjacent Expansion):

_______________________________________________________________

Phase 2 (Cross-Functional/Broader):

_______________________________________________________________

Phase 3 (Strategic Integration):

_______________________________________________________________

Simplicity checkpoints—what customization requests will you resist?

_______________________________________________________________

---

**EVALUATION SCHEDULE**

Weekly check: _____________

Monthly review: _____________

Quarterly assessment: _____________

Key metrics to track:

_______________________________________________________________

Decision framework (continue/expand/modify/pause/abandon criteria):

_______________________________________________________________

---

### Takers/Shapers/Makers Decision Matrix

*Complete before every implementation decision.*

**Choose TAKERS (67% success rate) if:**
- [ ] Proven vendor solutions exist for this use case
- [ ] Your needs are similar to other organizations
- [ ] You want fastest time-to-value (4-8 weeks)
- [ ] Resources are limited
- [ ] Risk tolerance is low
- [ ] This is your first AI implementation in this area

**Choose SHAPERS (45% success rate) if:**
- [ ] Industry-specific requirements exist that vendors don't address
- [ ] Some customization needed but not building from scratch
- [ ] You have technical capability for configuration
- [ ] Timeline is moderate (8-16 weeks acceptable)
- [ ] Business case clearly justifies customization cost
- [ ] You've successfully implemented Takers solutions before

**Choose MAKERS (33% success rate) if:**
- [ ] True competitive differentiation requires custom solution
- [ ] No vendor solutions address your unique needs
- [ ] You have strong AI/ML engineering capability
- [ ] Timeline is flexible (16+ weeks acceptable)
- [ ] Strategic value justifies high investment and risk
- [ ] You've successfully implemented Shapers solutions before

**Default to TAKERS unless compelling, documented reasons exist for alternatives.**

Selected approach: _____________

Justification: _______________________________________________________________

---

### Scaling Readiness Checklist

*Complete before scaling from pilot.*

**Technical Readiness:**
- [ ] System performance stable under increased load
- [ ] Integrations reliable and documented
- [ ] Support processes can handle projected growth
- [ ] Security and compliance requirements met
- [ ] Simplicity preserved from pilot version (no scope creep)

**Organizational Readiness:**
- [ ] Leadership committed to continued investment
- [ ] Change management resources allocated
- [ ] Success metrics clearly demonstrate value (with evidence)
- [ ] Internal champions identified and empowered
- [ ] Resistance plan developed (skeptics addressed)

**User Readiness:**
- [ ] Pilot users can mentor or train others
- [ ] Training materials comprehensive and tested
- [ ] Support documentation covers common issues
- [ ] Onboarding process streamlined and fast
- [ ] Quality standards understood and accepted

**If any section has unchecked items:** Address before scaling. Scaling before readiness is a leading cause of implementation failure.

---

### Simplicity Audit Checklist

*Monthly check to avoid the customization trap.*

- [ ] Are we adding complexity that users didn't request?
- [ ] Could simpler approaches achieve 80% of the value?
- [ ] Are custom features actually being used (check usage data)?
- [ ] Is onboarding still as simple as during pilot phase?
- [ ] Do users prefer our solution to shadow AI alternatives?
- [ ] Can we migrate any custom builds to vendor solutions now?
- [ ] Are we still using Takers approach, or drifting toward Makers?
- [ ] Would a new user find this intuitive without extensive training?

**Scoring:**
- 6-8 checkboxes green: Simplicity maintained
- 4-5 checkboxes green: Complexity creep warning—review and simplify
- 3 or fewer green: Pause scaling. Simplify before continuing.

---

### Evaluation Tracking Template

*Track metrics across evaluation cycles.*

**Initiative:** ________________________________

| Metric | Baseline | Month 1 | Month 2 | Month 3 | Hypothesis |
|--------|----------|---------|---------|---------|------------|
| | | | | | |
| | | | | | |
| | | | | | |
| | | | | | |

**Monthly Notes:**

Month 1: _______________________________________________________________

Month 2: _______________________________________________________________

Month 3: _______________________________________________________________

**Quarterly Decision:** [ ] Continue [ ] Expand [ ] Modify [ ] Pause [ ] Abandon

Rationale: _______________________________________________________________

---

### SHAPE Enhancement Checklist

*Book-sourced gates and checks to strengthen each SHAPE phase.*

**Situation Enhancements:**
- [ ] Self-hosted vs. API decision documented (Infrastructure Decision Matrix)
- [ ] Shadow AI audit completed (what unofficial tools are users choosing?)
- [ ] Reality gap between documented and actual processes identified

**Hypothesis Enhancements:**
- [ ] Metric Readiness Gate passed (all 5 elements quantified)
- [ ] ROI Reality Check completed (no more than 2 red flags)
- [ ] Kill criteria are specific numbers, not vague conditions

**Action Enhancements:**
- [ ] Communication Protocol defined for each stakeholder group
- [ ] Takers approach selected unless documented justification for alternatives
- [ ] Pilot updates lead with business outcomes, not technical status

**Process Enhancements:**
- [ ] Adoption Readiness Gate passed before scaling (all factors "ready")
- [ ] Complexity Creep Audit scheduled monthly
- [ ] Simplification triggers documented

**Evaluation Enhancements:**
- [ ] Build vs. Buy Re-evaluation on quarterly schedule
- [ ] Sunk cost bias explicitly addressed in reviews
- [ ] Sunset criteria defined for all custom solutions

---

## About the Author

Jim Christian helps organizations implement AI systematically through observation-based frameworks rather than ideological debates about AI's societal impact.

With over 30 years in technology consulting and digital transformation, Jim has worked across industries from Fortune 500 financial institutions to regional SMEs, consistently focusing on one question: What actually works?

This curiosity-driven approach led to the development of the PAST and SHAPE frameworks featured in this guide—systematic methodologies now used by organizations worldwide to turn scattered AI experiments into sustainable competitive advantages.

Jim is the author of Signal Over Noise, a weekly newsletter serving professionals who need practical AI implementation guidance without the hype.

Based in Valencia, Spain, Jim works with clients globally, bringing three decades of implementation experience to organizations ready to move from AI experimentation to systematic advantage.

**Connect:** [Newsletter](https://signalovernoise.at) | [Website](https://jimchristian.net)

---

*For ongoing AI implementation insights and strategic guidance, subscribe to Signal Over Noise at signalovernoise.at*

*For strategic clarity methodology, see The PAST Framework Field Guide.*

*PAST + SHAPE = Complete system from strategy to implementation.*

---

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
