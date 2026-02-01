# fuzzy-name-mapper


## Motivations

There are many challenges within the world of private market data - one of them being the lack of consitency amongst fund naming conventions. If you have mutliple sources of performance data for a given fund, and in each distinct report the fund name is different, this presents a challenge of how to establish that data as belonging to the same fund. The variations of these names are unpredictable and hard to model. True, a LLM could analyse the variety of fund names and make an educated guess regarding a pairing, however, in an environment where data accuracy is paramount, human intervention is best practice. Manually pairing the variation to the Source of Truth fund name is a tedious task if done using a tool like Excel. The tool i've built bring everything needed to make an formal pairing complete, without endless clicking and sourcing of unique identification codes etc.

With a simple interface, users can easily establish a link between a fund name variation and a source of truth fund name (As it would appear to a front-end user). The user selects the fund and is presented with n amount of best guesses. These guesses are sourced from a fuzzy match performed on a list of front-end fund names.

