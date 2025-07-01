# Jelly Tech Test

Thank you for taking the time to interview at Jelly!

*Please read this whole document before beginning any work.*

⏰ Please note that this challenge is designed to be completed in a relatively short amount of time. Focus on producing a functional solution, and feel free to note areas where you would improve or expand upon your implementation as if it were for a production-ready app.

🤖 We want to test you, not your AI, so please **write your own code without AI assistance**. (However, you may make notes on where you think AI would have helped.)

⁉️ The problem statement is intentionally vague — please document any assumptions you make along the way.

🗣️ The next stage of this interview will be to review your work and have an open conversation about the technologies involved and the decisions you made. **Please ensure that you have the tech test up and running on your computer for the follow-up interview.**

Good luck and have fun!

## Overview

The `/data` folder in the repository contains a data dump with various ingredients and their prices over time.

The `/backend` folder is where you should build your API.

## Requirements & Guidelines

💽 You have been provided with multiple files in `/data` which give you various ingredients and their prices over time.

🕸️ You are to create an application that allows you to create new recipes and view existing recipes, with their current cost to produce clearly displayed.

📈 You must build a GraphQL or REST API in TypeScript that interfaces with a **relational database** (e.g., PostgreSQL, MySQL, SQLite, etc.) to manage the recipe and ingredient data.

📦 Feel free to use any packages you deem necessary; however, please refrain from using any major frameworks such as Nest.JS or Adonis.JS. We want to see what you are capable of building from the ground up, rather than how well you can integrate existing libraries.

---

> ⚠️ **IMPORTANT:** Frontend implementation is **required only** if you applied for a **full-stack position**. If you applied for a **backend-focused role**, you can skip the frontend entirely.

### Frontend Implementation Guidelines

If applicable, you're encouraged to implement any frontend functionality that meaningfully represents the backend logic, which includes a CRUD server for recipes, ingredients, and price changes. All frontend code should be placed inside the `/frontend` directory. You're free to use any libraries you find valuable, though using **React.js** along with a **GraphQL/REST client** is preferred. Focus on clarity, usability, and how well your UI reflects the backend capabilities.

## Submission

1. **Commit your code** to a **private GitHub repo**.
2. **Add** `robert-jelly` and `dkjelly` so we can access your work.
3. **Send an email** letting us know you’re done and ready for review.
