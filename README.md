# Procrastination-finder
An interactive calculator for "The Procrastination Equation" that provides personalized, AI-powered strategies to help you stop procrastinating.
The Procrastination Equation - Interactive App

This is a single-page web application that brings Piers Steel's "The Procrastination Equation" to life. It helps you understand why you procrastinate by letting you interact with the core formula and provides AI-powered, personalized strategies to help you get started on your tasks.

View the Live Demo

(You will add your GitHub Pages link here after you publish it!)

Features

Interactive Calculator: Based on the book's core formula (Expectancy x Value) / (Impulsiveness x Delay), you can input your own values (as percentages) and see your "Motivation Score" calculated in real-time.

Dynamic Chart: Your Motivation Score is displayed on a bar chart that updates instantly as you press "Calculate".

Score Interpretation: A simple guide helps you understand what your score (High, Moderate, Tipping Point, or Low) actually means in practice.

✨ AI-Powered Strategies: If your motivation score is low, a special button appears. Clicking it calls the Gemini API to generate 3-5 personalized, actionable strategies that target your specific weak points (e.g., low confidence, high distractibility).

Book Summary: Includes browsable tabs with key concepts from the book and a list of general strategies to boost each of the four variables.

Technologies Used

HTML5: For the core structure.

Tailwind CSS: For all styling and layout (loaded via CDN).

JavaScript (ES6+): For all interactivity, calculations, and API calls.

Chart.js: For the dynamic motivation bar chart (loaded via CDN).

Gemini API: To generate personalized productivity advice.

How to Use

Open the App: Just open the procrastination_equation_spa.html file in any modern web browser.

Explore the Tabs:

Key Concepts: Get a quick summary of the book's premise.

Core Equation: This is the main calculator.

Key Strategies: Read general tips for improving your motivation.

Use the Calculator:

Go to the "Core Equation" tab.

For each of the four variables, enter a percentage (10-100) that reflects your feeling about the task.

Click "Calculate Motivation".

See your score on the chart and read the interpretation in the guide below.

Get AI Help:

If your score is below 1.0, the "✨ Get AI-Powered Strategies" button will appear.

Click it. The app will securely send your inputs to the Gemini API.

In a few seconds, a new section will appear with a custom list of strategies to help you.
