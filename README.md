# Project Goals

This project aims to understand when and why AI-supported decision tools succeed, fail, or backfire in international development settings. Rather than asking whether a tool is technically accurate, we focus on whether it is accepted, sustained, and beneficial in real communities over time.

Specifically, the project has three goals:

Identify human and psychological conditions that affect uptake. We study how risk perceptions, learning from experience, trust, and social influence shape whether communities adopt and continue using decision tools—and which forms of additional support can compensate for these constraints.
Understand how decision tools can cause long-run harm despite short-run success. We examine conditions under which tools that improve outcomes initially may increase vulnerability, reduce welfare, or undermine trust over time.
Assess how geography and environmental context shape uptake and persistence. We analyze how climate variability, environmental feedbacks, and geographical conditions influence whether the same tool succeeds in one place and fails in another, and how design or support can mitigate these differences.
Together, these goals aim to show not only whether decision tools work, but under what conditions they can be responsibly and effectively deployed.

# Approach

1. Purpose of the Model
This agent-based model (ABM) simulates how fishers in a local community decide whether to adopt and continue using an AI-supported fisheries app over time.
The model focuses on five core drivers of uptake:
•	Trust
•	Perceptions of risk
•	Learning from past outcomes
•	Peer influence
•	Environmental variability

2. Model Overview
The model represents a fishing community composed of individual fishers (agents) connected through a social network. Each season, fishers decide whether to use the app based on their trust, past experiences, perceived risk, and what their peers are doing.
Environmental conditions vary across seasons, influencing both fishing outcomes and how fishers interpret the app’s performance.
The model runs over multiple time periods (e.g., fishing seasons) and tracks how adoption evolves.

3. Agents
Each fisher is represented as an agent with the following characteristics:
3.1 Trust
Represents confidence in the app and the institution behind it.
Trust: - Increases gradually after positive experiences. - Decreases sharply after negative experiences. - Is influenced by the trust levels of peers.

3.2 Perceived Risk
Represents how risky it feels to rely on the app.
Risk perception: - Increases after bad outcomes. - Increases when environmental conditions are highly unpredictable. - Decreases when many peers successfully use the app.

3.3 Belief in Usefulness
Represents the fisher’s belief that the app improves outcomes (e.g., catch, safety, income).
Beliefs update over time based on personal experience.
Negative experiences may carry more weight than positive ones.

3.4 Adoption Status
Each season, a fisher either: - Uses the app - Does not use the app
Adoption is probabilistic and depends on trust, beliefs, perceived risk, environmental conditions, and peer behavior.

3.5 Social Network
Each fisher observes a set of peers.
Peer influence affects: - Willingness to adopt - Trust updates - Perceived risk
Fishers may copy behavior or confidence from their social contacts.

3.6 Resource Constraints
Represents a fisher’s ability to weather a bad season or absorb losses.
Resource-constrained fishers:
Are more vulnerable to single negative outcomes
May be more risk-averse about trying new approaches
Have less capacity to experiment or learn through trial and error
Face higher stakes in adoption decisions
Resource levels may also affect:
Persistence after setbacks
Willingness to invest time in learning the app
Ability to access complementary resources (fuel, equipment) that make the app more useful

3.7 Represents how far into the future a fisher weighs outcomes when making decisions.
Variation may reflect:
Age
Health status
Family obligations and succession planning
Alternative livelihood options
Fishers with longer time horizons:
May tolerate short-term uncertainty for long-term gains
May invest more in learning and skill-building
May be less deterred by initial setbacks
Time horizons interact with environmental variability. In highly volatile contexts, even patient fishers may discount the future more heavily.


3.8 Alternative Information Sources
Represents access to and trust in other sources of knowledge.
Sources may include:
Traditional ecological knowledge passed down through generations
Personal fishing experience
Observations of environmental cues (weather, water conditions, bird behavior)
Informal networks and elder fishers
Fishers with strong alternative information sources:
May be less dependent on the app
May use the app selectively rather than as a replacement
May evaluate app advice against traditional knowledge
May be slower to adopt if recommendations conflict with established practices
The relationship between traditional knowledge and app-based guidance may be:
Complementary (app confirms or refines existing knowledge)
Contradictory (app suggests different approaches)
Context-dependent (each works better in different conditions)

3.9 Technology Access and Literacy
Represents familiarity with smartphones and digital tools, as well as practical access.
Variation includes:
Prior experience with mobile phones or apps
Literacy and numeracy levels
Language compatibility
Physical access to devices (ownership vs. sharing)
Network connectivity and data costs
Fishers with lower technology literacy or access:
Face higher barriers to initial adoption
Require more support and training
May use the app less effectively even when adopted
May rely on intermediaries or facilitators
May experience the app differently (e.g., voice vs. text interface)
Technology constraints can create persistent inequality in adoption and benefits, even when the app is freely available.

4. Environment
Each season has a level of environmental variability.
Examples include: - Stable conditions - Moderately variable conditions - Highly volatile conditions (storms, shifting fish patterns, unusual weather)
Environmental variability affects: - The reliability of fishing outcomes - The clarity of feedback about whether the app is helpful - Perceived risk
Higher variability makes outcomes noisier and learning more difficult.

5. Seasonal Dynamics
Each season unfolds in the following sequence:
Step 1: Environmental Conditions Realize
The season is characterized by a specific level of variability.

Step 2: Social Observation
Fishers observe: - Which peers are using the app - Whether peers appear satisfied or dissatisfied

Step 3: Adoption Decision
Each fisher decides whether to use the app.
This decision depends on: - Trust - Belief in usefulness - Perceived risk - Environmental conditions - Peer behavior

Step 4: Outcomes Occur
Fishers experience fishing outcomes.
If using the app, outcomes may be: - Better than baseline - Worse than baseline - Ambiguous due to environmental noise
In volatile seasons, even a useful app may appear ineffective.

Step 5: Updating
Fishers update: - Beliefs about usefulness - Trust - Perceived risk
Highly visible failures may reduce trust across the entire community.

6. Possible System Dynamics
The model can generate multiple realistic patterns:
6.1 Gradual Diffusion
Adoption increases steadily as trust builds and peers influence others.

6.2 Fragility
A single extreme season reduces trust significantly.

6.3 Trust Collapse
A public or widely discussed failure causes rapid decline in adoption.

6.4 Persistent Inequality
Risk-averse or resource-constrained fishers may never adopt.

6.5 Context-Dependent Success
The same app may: - Succeed in moderately variable environments - Struggle in highly volatile environments

7. Policy and Design Experiments
The model allows simulation of interventions such as:
•	Training programs that accelerate trust-building
•	Human facilitation to reduce perceived risk
•	Subsidies lowering adoption barriers
•	Communication strategies after failures
•	Different network structures (central influencers vs decentralized communities)

8. Outputs Tracked
Over time, the model tracks:
•	Overall adoption rate
•	Trust distribution
•	Dropout rates
•	Sensitivity to environmental shocks
•	Differences across subgroups
•	Stability versus collapse of uptake



# Collaborators

The Positive Development™ Living Lab at Lake Malawi
Mzuzu University
