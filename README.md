# Interactive English Quiz - Lesson A1-17

## Overview

This interactive quiz is designed for students of Lesson A1-17 in an English language course, focusing on prepositions of place and key vocabulary from the lesson. Built using HTML, Tailwind CSS, and JavaScript, the quiz features three engaging sections: multiple-choice questions, a drag-and-drop preposition activity, and a vocabulary matching game. The quiz is responsive, visually appealing, and optimized for both desktop and mobile devices.

## Quiz Structure

The quiz consists of 16 questions across three parts, with a total score of 16 points:

### Part 1: Multiple Choice - Prepositions & Vocabulary (5 Questions)
- **Description**: Students select the correct preposition or vocabulary word to complete sentences.
- **Questions**:
  1. The bread is ___ the basket. (Correct: `in`, Slide 4)
  2. The tree is ___ the woman. (Correct: `behind`, Slide 4)
  3. The phone is ___ the stove and the sink. (Correct: `between`, Slide 9)
  4. Adam walks ___ the street. (Correct: `across`, Slide 8)
  5. God gave the ___ to Moses on the mountain. (Correct: `laws`, Slide 14)
- **Scoring**: 1 point per correct answer (5 points total).
- **Features**: Immediate feedback with animations (green for correct, red for incorrect).

### Part 2: Drag-and-Drop Prepositions (5 Questions)
- **Description**: Students drag prepositions (`in`, `behind`, `above`, `between`, `across`) to complete sentences.
- **Questions**:
  1. The sun is ___ the land. (Correct: `above`, Slide 4)
  2. The pen is ___ the book. (Correct: `in`, Slide 8)
  3. The teacher lives ___ the church. (Correct: `behind`, Slide 8)
  4. The phone is ___ the stove and the sink. (Correct: `between`, Slide 9)
  5. The boys walk ___ the street to school. (Correct: `across`, Slide 8)
- **Scoring**: 1 point per correct drop (5 points total).
- **Features**: Visual feedback with green (correct) or red (incorrect) drop zones and animations.

### Part 3: Vocabulary Matching Game (6 Questions)
- **Description**: Students drag vocabulary words (`laws`, `love`, `mountain`, `Lord`, `land`, `holy`) to match sentences with underscore placeholders.
- **Questions**:
  1. Rules given by God to ___. (Correct: `laws`, Slide 14)
  2. The Lord Jesus ___ us. (Correct: `love`, Slide 10)
  3. Moses led the people to a ___. (Correct: `mountain`, Slide 13)
  4. ___, do not have gods other than me. (Correct: `Lord`, Slide 15)
  5. God brought his people back to the ___. (Correct: `land`, Slide 17)
  6. He helps us have ___ lives. (Correct: `holy`, Slide 10)
- **Scoring**: 1 point per correct match (6 points total).
- **Features**: Purple-themed draggable words, with green (correct) or red (incorrect) drop zones and animations.

## Features

- **Responsive Design**: Adapts to mobile and desktop screens using Tailwind CSS utilities (`max-w-3xl`, `flex-wrap`, `gap`).
- **Visual Appeal**:
  - Gradient background (`bg-gradient-to-br from-blue-100 to-indigo-100`).
  - Rounded card layout (`rounded-2xl`) with shadow (`shadow-xl`).
  - Hover effects on draggable elements (`transform: scale(1.05)`).
  - Animations for feedback (`pulse` for correct, `shake` for incorrect).
- **Progress Tracking**:
  - Dynamic progress bar showing completion percentage.
  - Progress text (e.g., `0/16`) updates as questions are answered.
- **Scoring**: Displays current score (e.g., `Score: 0/16`) and updates in real-time.
- **Reset Functionality**: A "Reset Quiz" button clears answers, score, and feedback.
- **Optimized Code**:
  - Centralized multiple-choice questions in a JavaScript array.
  - Single event listener for multiple-choice questions.
  - `Set` for tracking answered questions to prevent score duplication.
  - Unified drag-and-drop logic for Parts 2 and 3.

## Alignment with Lesson A1-17

The quiz targets the first half of Lesson A1-17, focusing on:
- **Prepositions of Place**: `in`, `behind`, `above`, `between`, `across` (Slides 4, 8, 9, 11).
- **Vocabulary**: `laws`, `love`, `mountain`, `Lord`, `land`, `holy` (Slides 10, 11, 14, 15, 17, 19).
- **Learning Objectives**: Reinforces grammar (prepositions) and vocabulary comprehension through interactive activities.

## Setup and Testing Instructions

1. **Setup**:
   - Save the quiz code as `index.html`.
   - Ensure an internet connection for loading Tailwind CSS via CDN (`https://cdn.tailwindcss.com`).
   - No additional files are required (e.g., no audio files).

2. **Testing**:
   - Open `index.html` in a modern browser (e.g., Chrome, Firefox).
   - **Part 1**: Select answers in multiple-choice questions and verify feedback animations (green for correct, red for incorrect).
   - **Part 2**: Drag prepositions to sentences, check for correct/incorrect styling and animations.
   - **Part 3**: Drag vocabulary words to sentences with underscores (e.g., "Rules given by God to ___"), confirm correct matches update the score.
   - **Progress Bar**: Ensure the bar and text (e.g., `6/16`) update as questions are answered.
   - **Reset Quiz**: Click the "Reset Quiz" button to verify all elements (score, progress, feedback, drop zones) reset correctly.

## Development Notes

- **Artifact ID**: `79809c1f-6f59-4675-a50d-22548afc99ad`
- **Version ID**: `7d706187-be7e-44b4-9200-e902ab84cde9`
- **Date**: May 27, 2025
- **Optimizations**:
  - Refactored JavaScript for maintainability.
  - Used Tailwind CSS for rapid, consistent styling.
  - Ensured accessibility with focus rings and clear feedback.
- **Future Enhancements**:
  - Add local storage to save progress.
  - Include additional question types (e.g., fill-in-the-blank).
  - Integrate images or icons for visual learners.

## License

This quiz is intended for educational use within the context of Lesson A1-17. Redistribution or modification requires permission from the course administrator.
