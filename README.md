# Optimization-Project

##Overview:
This project revolves around the organization of a modern art exhibition at the San Francisco Museum of Modern Art, funded by Josh Riggs, a recent lottery winner and passionate artist. The exhibition aims to showcase a range of artworks from various emerging artists, with Josh Riggs and Celeste McKenzie, a museum director, at the forefront of curating the pieces.

##Problem Statement:
Josh and Celeste encounter several constraints and preferences in the selection process. Josh has a defined budget, specific inclinations towards certain art forms, personal biases for and against some artists, and a desire for diversity in the art forms displayed. Celeste, on the other hand, has her own objectives to maintain diversity among artists and to represent multiple social, environmental, and scientific themes. The museum's space limitation further complicates the selection process, with restrictions on the number of sculptures and other artworks that can be displayed.

##Requirements and Constraints:
Budget Limitation: The budget allocated by Josh for the exhibit is $4 million.
Art Form Diversity: The exhibition needs to include a varied range of art forms and painting styles.
Personal Preferences and Biases: The preferences and biases of Josh and Celeste towards specific artists and pieces need to be considered.
Social and Thematic Representation: Celeste aims to represent diverse themes and include pieces from diverse populations of artists, advocating for feminism, environmentalism, Native American rights, and scientific advancements.
Space Limitation: The museum has limited space, allowing only four sculptures and having wall space for 20 other artworks.
Objectives:
##Maximize Artwork Display: Given the budget and constraints, the primary objective is to maximize the number of pieces displayed in the exhibit.
Minimize Cost: Another objective is to minimize the cost of the exhibit while displaying at least 20 pieces, considering the requirements set by Josh and Celeste.
Include Specific Pieces: Certain pieces need to be included to represent different themes and to satisfy the preferences and biases of Josh and Celeste.
##Solution Approach:
Binary Integer Programming (BIP) Model: Formulate and solve a BIP model to address the constraints and objectives, ensuring the optimal selection of pieces within the budget.
Optimization for Minimum Cost: Adapt the model to minimize the cost of the exhibit, considering a minimum of 20 pieces to be displayed, while adhering to all requirements and constraints.
Consideration of Additional Funding: Evaluate scenarios where additional funding is provided by influential patrons to accommodate specific pieces and preferences.
##Outcomes:
The solution to this problem will provide a curated list of artworks to be displayed in the exhibition, considering all the constraints, preferences, and objectives outlined. The outcomes of the different models and scenarios will inform the decision-making process of selecting the artworks, balancing the artistic, thematic, and financial aspects of organizing the exhibition.

##Questions to Explore:
Maximizing Number of Pieces within Budget: How many and which pieces are displayed when maximizing the number of pieces within the allocated budget and given constraints?
Cost Minimization with Minimum 20 Pieces: How much does the exhibit cost and which pieces are displayed when minimizing the cost with at least 20 pieces displayed, considering the given requirements and constraints?
Impact of Additional Funding on Artwork Selection: How does the contribution from an influential patron impact the selection of pieces, and what is the minimum amount required to ensure the inclusion of specific artworks, keeping the total display to exactly 20 pieces?
