# Intelligent Car Configuration Recommender
Building AI course project

## Summary

This project proposes an AI-powered recommendation system that assists users in selecting the optimal car configuration based on their preferences, budget, and intended usage. The system should analyze user needs and compare them with historical configuration data and vehicle specifications to generate personalized recommendations.

## Background
Modern car configurators offer a wide range of customization options, such as materials and colors. While such flexibility is valuable, it often leads to choice overload. 
Consider configuring a Ferrari 296 GTS. One needs to balance such multiple factors as performance and comfort, or aesthetics and cost. 
Existing configurators do not provide intelligent guidance. Users must manually evaluate complex combinations, often without understanding how different options interact.
This project aims to solve this problem by introducing an AI system that recommends configurations aligned with user profiles and highlights the reasoning behind each suggestion.

## Data sources and AI methods
The data sources include core vehicle specifications, available configurations, and user preferences.
While the AI methods could include collaborative filtering, used to recommend configurations based on similar users’ choices or simulated annealing.

## How is it used?

The user can provide all their preferences, then the system evaluates different configurations, returning the top 3 to 5 configurations explaining why each configuration satisfies the user’s requests.

## Example
A user with: large budget, focus on track use, preference for carbon fiber and "total black look". They will receive as their first configuration for their 296 the following:

An all black configuration with Fiorano package: 

![image alt](https://github.com/ant05-pixel/my-new-project/blob/ecd2a6125e98103cdeea968302511d4aaa5a34a6/Screenshot%202026-04-09%20185524.png)

With a similar description: this configuration satisfies all the user’s preferences using carbon fiber options wherever applicable and preferring black customizations.

One other similar configuration but with Silver Nürburgring livery and matching brake calipers: 

![image alt](https://github.com/ant05-pixel/my-new-project/blob/25f4f58871198ddbaa84d29895314ac0189c541a/Screenshot%202026-04-09%20185315.png)

With a similar description: this configuration satisfies most of the user’s preferences using carbon fiber options wherever applicable but instead of an “all black look”, there were added Silver Nürburgring livery and aluminum brake calipers that match the livery for a more “track focused” look.

## Challenges 
The system will have a "cold start" problem as it is more difficult to suggest configurations for new models without historical data from other users (though it will work nonetheless). And while users may not fully agree with the system’s recommendations, the system's primary purpose remains that of aid in decision-making, rather than its replacement.

## What next 
In the future, the system could be improved by exending it to compare different car models, or possibly a customer collection to create a configuration that fits with the rest of the user's garage.

## Acknowledgments
Images from Ferrari car configurator: https://carconfigurator.ferrari.com/it_IT
