---
description: By Hugo Silva - 1231428@isep.ipp.pt - 29/05/2024
---

# What is the Fragmented Documentation Smell

Fragmented Documentation Smells refer to issues that arise from disorganization or incompleteness, leading to poor developer experience. Smells helps us identify problems within documentation and understand and create documentation more clear and effective. This is the main definition of the smell, being one of the more brief descriptions available at [Automatic Detection of Five API Documentation Smells: Practitioners' Perspectives](references.md). Some of the main principals that can be extracted from said definition are:

1. **Scattered Information:** Information related to a single concept or idea is dispersed throughout the documentation instead of being organized in a single block of information. It makes the search for all the necessary details more complex and tiresome.
2. **Inconsistent Terminology:** If different parts of the documentation use different terms and naming conventions for the same concepts, that makes the document more complex and harder to understand.
3. **Incomplete Examples:** This happens when well... examples are incomplete. Code blocks have incomplete implementation, written examples have incomplete context or none at all. This makes it harder for developers to test the API described and to understand its functionality to its fullest.
4. **Outdated Information:** Outdated information in an API can lead to wrong implementations by the developers, creating a discrepancy between the documentation and the actual API behavior.
5. **Missing Links:** The documentation can benefit from well used hyperlinks that facilitate the navigation and search process of the documentation. Without these shortcuts, the developer is forced to manually search the whole document to get to the desired information.
6. **Redundant Information:** Including repeating information without clear reasoning can lead to inconsistencies if one of those sections is updated and the others not.
7. **Poor Structure and Navigation:** The lack of a clear structure and navigation flow makes it difficult to developers to follow and understand the documentation.
8. **Sparse Descriptions:** Description of the API endpoints are too brief or general.
9. **Lack of context:** Documentation that fails to provide the necessary reasons for its existence only tend to cause confusion among developers that use the documentation. This leads developers into guessing and making incorrect assumptions about the documented API.
10. **Missing Cross-References:** Similar to missing links, not connecting related functionalities through navigation systems can cause developers to hunt the necessary information unnecessarily and without guidance.

