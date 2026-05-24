# Complete Course Plan — Agentic in 3 Tracks

## 1. Analysis of the current project content

The project today is focused on support materials within`doc/`and does not yet have the course structure in HTML.

### Core files found

-`doc/conteudo_agentic_sessao.md`
- `doc/agentic_workflows_guia_completo.md`
- `doc/resuam todo os topicos.txt`- images and a video in`doc/`### What the current content covers well

- definition of Agentic AI and agentic workflows
- difference between chatbot, traditional and agentic automation
- WAT framework: Workflows, Agent, Tools
- example of an automated newsletter
- basic system planning
- use of credentials and`.env`- testing and continuous improvement
- market narrative, value, ROI and consultative selling

### Main problem of current material

The content is strong in introduction, positioning and commercial narrative, but is still shallow in terms of implementation, architecture, operation and pedagogical progression.

### Gaps to transform into a complete course

- minimal technical fundamentals for beginners
- drawing real workflows step by step
- tools, APIs, webhooks and data formats
- context, memory, state and persistence
- skills, MCP and integrations
- evaluation, testing, observability and cost
- security, guardrails and operational limits
- deploy, scheduling and operation in production
- complete case studies
- exercises, projects and deliverables per module

## 1.1 Recommended direction to fill in the gaps

If the objective is to develop **agentic engineer** talent, the course should reduce passive theory and increase operational training.

### Recommended focus

- design tools with clear schema and explicit limits
- decompose problems into testable workflows
- define inputs, outputs and success criteria
- inspect traces and debug execution failures
- create evals and graders to measure quality
- work with human approvals and guardrails
- operate real integrations with state, memory and logs
- deploy, observability and continuous improvement

### What to avoid as a central focus

- excess motivational class on the future of the market
- excessive conceptual comparison without implementation
- beautiful demos without reliability criteria
- very generic modules about AI without practical artifact

## 2. Recommended structure in 3 trails

The best division for this project is to separate the course by maturity and objective:

1. Track 1: Agentic Fundamentals
2. Track 2: Construction and Operation of Agentic Systems
3. Track 3: Market Application, Consulting and Products

This division takes advantage of the current material in tracks 1 and 3 and creates a more technical track 2, which is currently the biggest gap in the project.

## 3. Detailed track structure

## Track 1 — Agentic Fundamentals

### Objective

Provide a minimal conceptual and technical basis for those who are still transitioning from chatbots and traditional automation.

### Suggested modules

#### Module 1. What is Agentic AI

- central concept
- why does it matter now
- difference between chatbot, automation and agentic
- types of problems that agentic solves best

#### Module 2. Technical fundamentals without hassle

- how APIs work
- what are webhooks
- JSON, files, inputs and outputs
- environment variables and credentials

#### Module 3. WAT Structure

- Workflows
-Agent
-Tools
- how each part connects
- when to use deterministic flow vs agentic flow

#### Module 4. How to think about objectives, context and restrictions

- clear objective
- success criteria
- mandatory entries
- expected outputs
- agent rules and limits

#### Module 5. Skills, tools and reusable context

- what is a skill
- how to organize reusable instructions
- tool use patterns
- brand, style and business context

#### Module 6. First guided agentic workflow

- simple example of research + structuring + delivery
- decomposition into steps
- most common beginner mistakes

### What can be reused from the current project

- almost all current conceptual content
- comparisons between chatbot, automation and agentic
- WAT
- newsletter example

## Track 2 — Construction and Operation of Agentic Systems

### Objective

Teach how to design, build, test and operate real agentic systems.

### Suggested modules

#### Module 1. Architecture of an agentic system

- input, planning, execution and output
- system components
- orchestration
- separation between agent, tools and runtime

#### Module 2. Designing reliable workflows

- task decomposition
- decision points
- fallback
- retry
- checkpoints
- human in the loop

#### Module 3. Tools and integrations

- reading and writing files
- API consumption
- database
- email
- scraping and searching
- generation of artifacts
- tool schema design and input/output contracts
- when to require human confirmation before action

#### Module 4. Memory, context and persistence

- temporary vs persistent context
- execution history
- state storage
- how to avoid loss of context

#### Module 5. Tests, evals and debugging

- flow tests
- limit cases
- exit validation
- traceability
- how to measure quality
- traces and trace grading
- objective and subjective graders
- regression between prompt, tool and workflow versions

#### Module 6. Security and governance

- agent access scope
- credential protection
- destructive actions
- human confirmations
- basic compliance
- isolation of unreliable data
- prompt injection and use of structured outputs

#### Module 7. Deploy and operation

- local execution
- scheduled execution
- webhooks
- queues
- monitoring
- costs and limits
- trace observability
- retry and fallback strategy in production

#### Module 8. Complete practical project

- build an end-to-end workflow
- document architecture
- test
- publish

### Current project gap

This track almost doesn't exist in the current material and needs to be produced practically from scratch.

### Ideal format for this track

Each module must end with an observable engineering artifact:

- workflow specification file
- JSON tools contract
- minimal eval suite
- security checklist
- log or trace analyzed
- executable mini project

## Track 3 — Market Application, Consulting and Products

### Objective

Transform technical knowledge into business value, service, consultancy or product.

### Suggested modules

#### Module 1. Identifying real bottlenecks

- how to diagnose processes
- where agentic generates value
- when NOT to use agentic

#### Module 2. Use cases by area

- marketing and content
- sales and CRM
- service
- operations
- financial
- HR

#### Module 3. Scope and proposal

- discovery
- current process map
- design of the future solution
- risks and assumptions

#### Module 4. ROI and pricing

- hours saved
- cost avoided
- increase in revenue
- price per value delivered

#### Module 5. Delivery to customer

- onboarding
- access collection
- validation
-rollout
- handoff and maintenance

#### Module 6. Portfolio and product

- transform a project into a case
- package services
- create recurring offer
- evolve from freelancer to strategic partner

#### Module 7. Business Capstone

- diagnose a company
- propose workflow
- calculate ROI
- design implementation

### What can be reused from the current project

- bottleneck analogy
- value generated vs price per hour
- freelance path -> consultant -> strategic partner

## 4. Recommended pedagogical order

If the student takes the full course:

1. Track 1 first
2. Track 2 after
3. Trail 3 last

If the audience is more technical:

1. Condensed Track 1
2. Complete trail 2
3. Track 3 as a specialization

If the audience is a consultant, strategist or agency owner:

1. Track 1
2. Track 3
3. Trail 2 as technical deepening

## 5. Suggested reorganization of current content

### Content that can quickly become classes

- introduction to agentic
- comparison with chatbot and automation
- WAT framework
- newsletter workflow example
- why the market is growing
- skills and business models

### New content that needs to be created as a priority

- technical fundamentals: API, webhook, JSON, auth,`.env`- workflow design and orchestration
- tools and integrations in practice
- memory and context
- tests and evals
- deploy and operation
- security and guardrails
- 2 or 3 complete practical projects

## 6. Suggested course anchor projects

To give unity to the course, I recommend 3 main projects:

1. Research and synthesis assistant
   - good for Trail 1
2. Agentic workflow of content or operation with tools
   - good for Trail 2
3. Diagnosis and agentic proposal for real company
   - good for Track 3

## 6.1 Recommended practical projects to develop agentic engineering talent

For the course to be truly educational, I recommend exchanging part of the lectures for progressive laboratories.

### Laboratory 1. Tool calling basic

- design 3 tools with schema
- test valid and invalid inputs
- observe when the agent calls the wrong tool
- refine description and parameters

### Laboratory 2. Deterministic workflow + agentic stage

- separate what must be fixed from what can be decided by the agent
- create checkpoints
- validate final output against objective criteria

### Laboratory 3. Memory and status

- save minimum history
- resume an execution
- distinguish session context and persistent context

### Laboratory 4. Evals and trace debugging

- create small dataset of cases
- run evaluation
- analyze traces
- fix failure without worsening cases that already worked

### Laboratory 5. Safety and human approval

- limit scope of tools
- block destructive operations without approval
- test malicious entry scenarios

### Laboratory 6. MCP in practice

- expose or consume a simple MCP server
- test resources, prompts and tools
- inspect integration capabilities and errors

### Laboratory 7. Deploy and operation

- set a workflow to run per event or schedule
- instrument logs
- measure cost, latency and failure rate

## 6.2 Agentic Engineer Talent Rubric

The student must leave the course being able to demonstrate:

- clarity to define operational objective
- ability to decompose tasks into reliable steps
- criteria for deciding between fixed flow and agent decision
- mastery of tool design and schemas
- ability to debug real traces and crashes
- ability to measure quality with evals
- strong understanding of security, approvals and scope
- maturity to operate workflows in production

## 7. Reliable external references to fill in the gaps

The recommendations below are based on official documentation and primary specifications. The pedagogical inference here is: these sources point out that training a good agentic engineer requires training mainly in workflow design, tool use, security, evals and observability.

### OpenAI

- Agents SDK: handoffs, tools, streaming and traces
- Agent Builder and Node Reference: composition of workflows and flow control
- Agent Evals, Trace Grading, Graders and Prompt Optimizer: measurement, regression and continuous improvement
- Safety in building agents: guardrails, approvals, unreliable data and risk reduction

### Anthropic

- implementation of tool use: definition of tools, schemas and best practices
- web search, bash and code execution: real integration patterns
- streaming tools and token efficiency: operational tradeoffs

###MCP

- lifecycle and capability negotiation: architecture and interoperability
- tools: exhibition contract and human-in-the-loop
- inspector: debugging MCP servers
- design principles: composability and convergence of patterns

## 8. Conclusion

The current project already has a good nucleus to open a course, but it is not yet ready as a complete course. The existing base supports well:

- the promise of the theme
- conceptual introduction
- model comparison
- the business value layer

What's missing to complete a strong course is mainly the intermediate technical track, with construction, operation, tests and practical cases.

If the focus is developing agentic engineering talent, the right decision is to reorganize the course so that the student produces artifacts, debugs failures, runs evaluations and operates real workflows, instead of just consuming conceptual explanations.

## 9. Recommended next action

If the idea is to transform this into an educational product now, the most efficient sequence is:

1. close the final grid of the 3 tracks
2. define modules per track
3. map the current content to each module
4. list the new classes needed
5. create the`index.html`of the course and the`index.html`of each track
6. produce the modules in HTML in duclub format