# WWDC21 Swift Student Challenge Submission
## Accepted

## What's This?
### Part 1: Welcome/Tutorial
In part 1, the learner gets to understand the environment they are in, the dungeon, and get some context as to why they are there. The learner is also introduced to tools such as the natural language chatbot - T Krobot, that will be present throughout the journey. Clicking on the character reveals a full chat window where learners can ask the bot anything, from SwiftUI questions to jokes. T Krobot is available in every part to guide the learner through the escape room. The learner will also get a SwiftUI quick reference guide on the basics required to do the later tasks such as Buttons, VStacks, HStacks and State variables.

## Part 2: Getting Around
Part 2 is where the learner transitions into a first-person view of the scene and can move around freely. 

## Part 3: Task 1 - Locked
When the learner clicks on the chest, they will see that it is locked. Using SwiftUI modifiers like .background, .foregroundColor, and through changing the text, the learner must ensure the top row looks identical to the bottom row to unlock the chest. This teaches the learner how to use modifiers in SwiftUI.

## Part 4: Task 2 - Torn
When the learner eventually unlocks the chest, they will find a torn document. Using HStacks and VStacks, they can piece the document together in order to progress onto the next stage. This part teaches the learner about alignment in SwiftUI using VStacks and HStacks.

## Part 5: Task 3 - Door
After getting the document, the learner can travel to the exit and will learn about a vulnerability in one of the doors. They can then unlock it by editing the source code of the door. This part is meant to teach the learner about how State variables work and how they interact with one another.

## Technologies Used
**Natural Language** is used in the chatbot to generate a response using sentence embedding while sentiment analysis is used to give emoji reactions to certain messages.

**SceneKit** is used to create the interactive 3D scene that allows the learner to move around and explore the escape room, creating a unique learning experience.

This Playground is built using **SwiftUI** and **UIKit** for the user interface.

**PlaygroundSupport** is used to perform input validation on the Playground Page text for the various tasks and puzzles, ensuring that the responses provided were correct.
