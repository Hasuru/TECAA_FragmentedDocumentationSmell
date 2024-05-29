---
description: By Hugo Silva - 1231428@isep.ipp.pt - 29/05/2024
---

# Examples

Let us take the example of the PokéAPI's Contest Group of endpoints and Resources available at [PokéAPI Documentation](https://pokeapi.co/), taking into account possible problems that the [Fragmented Documentation Smell](what-is-the-fragmented-documentation-smell.md) enunciates.

When evaluated, the following issues were identified:

**Scattered Information**&#x20;

* Both contest effects and super contest effects are documented separately. This separation can make it harder for users to understand the overall impact of moves in contests and super contests without cross-referencing both sections, since both are very similar.

**Inconsistent Structuring**

* The structure of the JSON responses for Contest Effects and Super Contest Effects are similar but not identical. This difference can cause confusion as users may expect a uniform structure when dealing with similar types of data.

**Redundancy and Overlap**

* Some information, such as language resources, are repeated across different sections. This redundancy can make the documentation harder to navigate and maintain.
* Each effect and flavor text entry includes language data, which is repeated across various entries and sections.

**Navigation Difficulties**

* There is no centralized location where users can get an overview of all contest-related information. Users must navigate to each endpoint individually to piece together a full understanding of the contests.

Even though the documentation clearly has some flaws, there are also positive sides to it. The contest type endpoint is very well defined and overall the descriptions of each of the endpoints are brief but effective. The return values of each of the endpoints are also very well defined, with a further schema table explaining each type used and available in the API.&#x20;
