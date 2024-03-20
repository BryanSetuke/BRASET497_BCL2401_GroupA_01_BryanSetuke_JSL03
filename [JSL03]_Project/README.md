# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

Loom Recording Link: [Insert Link]

# Project Overview

In this project, you will be presented with two JavaScript code examples, each demonstrating a different programming paradigm: imperative and declarative. Your task is to analyse these examples and determine which one follows an imperative programming style and which one follows a declarative programming style. 

You will present your reasoning for each example, record your presentation using Loom, and submit your findings along with the Loom recording to the Project Tab on the Learning Management System (LMS).

# Instructions

## Step 1: Clone the Repository

Repo Link: https://github.com/CodeSpace-Academy/Module_3_StudentNo_Classcode_Group_Name-Surname_JSL03

1. Access the provided repository containing the starter code and presentation template.
2. Clone the repository.
3. Open the cloned repository in your preferred code editor.

## Step 2: Analyze the Examples

1. In the cloned repository, you will find two JavaScript code examples labeled "Example 1" and "Example 2."
2. Examine each code example and determine which one follows an imperative programming style and which one follows a declarative programming style.

## Step 3: Record Your Presentation

1. Use Loom (https://www.loom.com/).
2. Create a single video presentation for both examples that include the following:

   - Introduction of the example number.
   - Explanation of whether the example is imperative or declarative.
   - Detailed reasoning for your choice, discussing the code logic and style used in the example.
   - Mention any specific code structures or patterns that align with the chosen programming paradigm.
   
3. Keep each video presentation concise, with a maximum length of 2 minutes for each example. Your total recording time should not exceed 5 minutes.

## Step 4: Insert Loom Links

1. After recording, upload your presentation videos to Loom.
2. Obtain the Loom recording links for the video presentation.
3. Edit the `README.md` file in the cloned repository and insert the Loom recording links.
   
## Step 5: Submit Your Project
1. Commit your changes to the Git repository and push them to your GitHub account.
2. Ensure that the repository is public so that it can be accessed.
3. Submit the GitHub project link (URL) that includes your Loom recording link to the [JSL03] Project Tab on the LMS for evaluation.

# Project Evaluation

Your project will be evaluated based on your ability to:

- Accurately identify and differentiate between imperative and declarative programming styles.
- Provide clear and well-reasoned explanations for your choices.
- Present your findings concisely within the specified time limit.
- Follow the submission instructions accurately.

Follow the steps outlined above to complete the project successfully.

# Presentation Talking Points

Example #: 1

## Imperative Approach [2 Minutes]
1. **Step-by-Step Explanation:**
- The code defines a function `cookSteak` which takes `steakWeight` and `desiredDoneness` as parameters.
- It initializes variables `grillTemperature` and `steakTemperature`.
- It clearly spells out what is done in each step of the process of preparing the meal: preheat of the grill, occasioning of the steak, grilling, and serving.
- The while loop is used to continuously check if the steak's temperature has reached the desired doneness.
- It tracks the state of the grill temperature and steak temperature using mutable variables.

2. **Emphasis on How:**
- In other words, the approach to the imperative provides specification with respect to how will each and every step of it be carried out in a detailed order.
- It heavily uses mutable variables and explicit control flow (loops, conditions) to respect this state and progress.
- Preheat grill, season steak, check the temperature: ascertain easy preheating steps, seasoning the beef, and checking temperature by following the forthcoming recipe.


Example #: 2

## Declarative Approach [2 Minutes]
1. **High-Level Process Description:**
- The code defines a function `cookSteak` which takes `steakWeight` and `desiredDoneness` as parameters.
- It organizes the cooking process steps as objects within an array `cookingProcess`.
- In the array, the description of each object may be given; an overall meaning of the step is afforded but detail not in the performance of the step.
- The function iterates over `cookingProcess`, executing each step in sequence.

2. **Use of Data Structures:** - The declarative approach abstracts away the implementation details of each cooking step. It is "Data-Driven" in the sense that the cooking steps are appropriately abstracted out in a data structure (the array of objects), thus providing proper meaning. In other words, instead of saying exactly how everything will look in each case, the codes mainly describe the overall flow of action and what the expected acting at every point would be.

# Learning Outcome [1 Minute]
- Analyzing code in different paradigms reveals:

    1. Imperative: Explicit steps, precise but verbose. 
    2. Declarative: Abstracted, concise but less detailed.

- Imperative manages state directly, suitable for fine control. Declarative minimizes state, enhancing maintainability.
- Choose based on problem domain: Imperative for specific tasks, declarative for higher-level concepts.
