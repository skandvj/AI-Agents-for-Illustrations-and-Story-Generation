# AI Story and Illustration Generator

An AI-powered system that leverages modular agents to automatically generate children's storybooks, combining engaging storytelling with dynamic illustrations.  
Built using [Dify](https://dify.ai/) for agent orchestration.

---

## 🚀 Overview

This system is composed of multiple AI agents working together:
- **Feature Extractor**: Extracts key themes and story elements from user input.
- **Story Generator**: Generates creative story content based on extracted features.
- **Illustration Generator**: Creates illustrations matching the story scenes.
- **Storybook Content Crawler** (optional): Enhances the storybook with additional content.
- **Workflow Orchestrator**: Connects all agents to create a fully automated pipeline.

---



## 🛠️ How to Deploy

1. **Setup Dify**  
   Create a [Dify](https://dify.ai/) account if you don't have one.

2. **Import Agents**  
   - Go to **Create New App** → **Import Workflow**.
   - Upload each `.yml` file from the `agents/` folder.

3. **Configure Agents**  
   - Set environment variables, API keys (if required), and model settings as needed.
   - Test each agent individually.

4. **Run Workflow**  
   - Use the `story_and_illustration_generator_workflow.yml` to automate story and illustration creation.
   - Output: Full story with corresponding illustrations, ready for publishing.

---

## 🧩 Tech Stack

- **Dify** — AI agent orchestration platform.
- **Large Language Models (LLMs)** — For story and feature generation.
- **Generative AI (Diffusion Models)** — For illustration generation.

---

## 🧠 System Architecture

<img width="352" alt="image" src="https://github.com/user-attachments/assets/f67398ee-f8a6-48c5-845f-bc875d2da24f" />

