# Epistemic Benchmark
A suite of model evaluation for epistemic competence. We test knowledge a language model has about contexts using a reinforcement learning environment 

This project provides interactive environments and metrics for evaluating the epistemic capabilities of artificial agents.

### Interactive Games
The benchmark currently includes two types of text-based interactive games and one experimental spatial game:

**Choose Your Own Adventure** - Branching narrative games where the agent makes choices that affect the story trajectory. Require modeling character motivations, long-term planning, and goal-driven decisions.

**Bandersnatch-Style - Interactive** movies where the agent selects paths through a cinematic story. Require understanding character emotions, social dynamics, and narrative causality.

**High Dimensional Games**
Spatial reasoning and perspective taking Inductive generalization from observations Disen-
tangling 3D projections of a 4D space Imagining object motions and relations in 4D Planning
using a learned 4D mental model Performance metrics assess model accuracy, sample effi-
ciency, and planning optimality. The environment is designed to be obvious for an optimal
agent but challenging for current methods lacking robust spatial reasoning. Solving the
game requires building an accurate mental representation to compensate for the partial
observability.

<img width="356" alt="image" src="https://github.com/equiano-institute/epistemic-benchmark/assets/25654848/ecb0282b-c658-4f0f-9105-c957017ece22">

Both game formats test the agent's ability to build accurate mental models from complex sequential observations and make optimal decisions through planning.

# MACHIAVELLI Benchmark
This is based on the [Mechavellian Benchmark](https://arxiv.org/abs/2304.03279)

![image](https://github.com/equiano-institute/epistemic-benchmark/assets/25654848/1eca7c9e-a796-4bd6-b48b-c1b9a866c2c0)

## Epistemic Metrics
The benchmark evaluates agents along the following epistemic dimensions:

Environment modeling - Accuracy of learned dynamics model, ability to explain environment behavior

Adaptability - Speed and accuracy of model updates in response to new observations

Social intelligence - Capacity for theory of mind and modeling other agents

Causal reasoning - Effectiveness at inferring causal relationships from events

Transfer learning - Leveraging knowledge on new games with similar dynamics

Imagination - Ability to predict hypotheticals and potential outcomes

Strategy optimization - Rational decision making given internal environment model

## Choose-Your-Own-Adventure

## Bandersnitch Movie Game Options


![image](https://github.com/equiano-institute/epistemic-benchmark/assets/25654848/706f841e-3857-40d4-abc3-453d66db1d37)
