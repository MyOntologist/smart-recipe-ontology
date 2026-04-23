# Smart Recipe Ontology (SRO) - Requirements Specification

## 1. Purpose
The purpose of the Smart Recipe Ontology (SRO) is to provide a knowledge model for cooking recipes. The ontology should hold all knowledge required for cooking a dish according to a recipe, so that users could query for recipes according to various criteria (e.g. diet, calorie count, etc.). Information about recipe steps, required ingredients and utilities should also be provided by the knowledge model.

## 2. Scope
The focus of the ontology should be the recipe and its structure. Ingredients and utilities required for the recipe should be referenced, however this should not be an ontology for food or cooking equipment.

## 3. Implementation Language (optional)
* Ontology Web Language (OWL)

## 4. Intended End-Users (optional)
* People who want to cook specific recipes according to certain criteria (e.g. diet, calories, etc.)

## 5. Intended Uses
1.  Searching for fitting recipes based on several filter criteria.
2.  Providing information about the overall recipe as well as its subsequent steps so that the user can cook the corresponding dish.

## 6. Ontology Requirements

### a. Non-Functional Requirements
* **NFR1:** The ontology should support English.

### b. Functional Requirements
*Lists or tables of requirements written as Competency Questions and sentences*

| ID | Competency Question (CQ) |
| :--- | :--- |
| **CQ1** | Which recipes are used for vegetarian / vegan cooking? |
| **CQ2** | Which recipes use a specific set of ingredients? |
| **CQ3** | Which ingredients are used in a recipe? |
| **CQ4** | How many calories does the overall dish from a recipe have? |
| **CQ5** | How long does it take to cook a dish according to a recipe? |
