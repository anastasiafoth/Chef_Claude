# Chef Claude

> A React + Vite recipe helper app that lets you generate ingredients and instructions from a text prompt.

## 🚀 Project Overview

`Chef Claude` is a simple cooking assistant built with React and Vite. Users enter a meal description, and the app returns a suggested recipe with ingredient list and step-by-step instructions. It’s perfect as a learner project and a base for integrating AI-powered recipe generation.

## 🧩 Features

- Prompt input for recipe ideas
- Dynamic result display in `ClaudeRecipe` component
- Ingredient breakdown with `IngredientsList`
- Clean UI layout with `Header` + `Main`
- Vite hot reload during development

## 📁 Project Structure

- `index.jsx`: app bootstrap
- `App.jsx`: top-level state + compositing
- `AI.js`: recipe prompt generation / sample data logic
- `components/ClaudeRecipe.jsx`: recipe output card
- `components/Header.jsx`: title + description
- `components/IngredientsList.jsx`: list renderer
- `components/Main.jsx`: prompt form and action flow
- `index.css`: global styles
- `package.json`: deps + scripts
- `vite.config.js`: Vite configuration

## 🛠️ Prerequisites

- Node.js 18+ (recommend latest LTS)
- npm or yarn

## 💻 Local Setup

1. `cd chef-claude`
2. `npm install`
3. `npm run dev`
4. Open `http://localhost:5173`

## ✅ Available Scripts

- `npm run dev`: start Vite development server
- `npm run build`: production build
- `npm run preview`: preview build locally

## 🔧 Development Notes

- UI is component-driven and easy to extend
- Add OpenAI/GPT API integration in `AI.js` to fetch real recipe content
- Keep prompt formatting in `AI.js` (or move to backend) for better maintainability

##  Future improvement

- add state persistence (localStorage)
- support saved recipes/favorites
- language translation and dietary restrictions filter
- backend endpoint with real AI recipe generation

##  License

MIT

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).
