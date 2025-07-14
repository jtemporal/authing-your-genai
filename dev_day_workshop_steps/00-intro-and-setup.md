# Introduction to Tool Calling and Assistant0 set up

Let's get started! Our assistant named Assistant0 is an AI personal assistant that consolidates your digital life by dynamically accessing multiple tools to help you stay organized and efficient.

It is built in NextJS and we'll add tool calling to it to make it more powerful.

## What is tool calling

Tool calling is the way we call the integrations your GenAI-powered application has in order to gain some ability to interact with external services, for example, interface with Gmail and Google Calendar to help you speedily draft emails and schedule meetings. It allows your AI agent to go beyond its pre-trained knowledge and interact with the real world, access private data securely, and perform actions on behalf of the user.

## Integrations we will implement during the workshop

We are going to add two integrations:

1. **Calculator**: So our assistant can learn how to do calculations; and
1. **Gmail Integration**: The assistant can scan your inbox to generate concise summaries. It can highlight urgent emails, categorizes conversations by importance, and even suggests drafts for quick replies.

## Set Up

1. Clone the Repository:
  ```bash
  git clone <your-repository-url>
  cd <your-repository-name>/auth0-assistant0
  ```

2. Install Prerequisites:
  * Ensure you have Node.js (v20 or later recommended, matching the blog post's suggestion) and npm/yarn/bun installed. The blog post specifically mentions `Bun v1.2` or `NodeJS v20`.
  * Visual Studio Code (latest version recommended).

3. Install Dependencies: Open the project in VS Code. Open the integrated terminal (View > Terminal).

  ```bash
  npm install
  # or
  bun install
  ```

4. OpenAI account:
  * Make sure you have an [OpenAI account and an OpenAI API key](https://platform.openai.com/docs/libraries#create-and-export-an-api-key).
  * Save the OpenAI API key to your `.env.local`.

Once the project is ready and you have your OpenAI API key in `.env.local`, you'll be ready continue on.

### Setting up your Auth for GenAI Auth0 account

For this workshop, you will need an Auth0 account, if you already have an Auth0 account you need a new Tenant to get the Auth For GenAI features.

### Why do I need a new tentant?
Since our "Auth for GenAI" feature is currently in Developer Preview, you must create a new tenant to ensure the necessary features are automatically enabled and configured for our session.


[Navigate to this page](https://auth0.com/ai/docs/user-authentication) and follow the first two pre-requisites steps in the image below.

![](images/00-1-setup-auth0-account-and-app-auth-for-genai-enabled.png)

Once you click **Create Account**, login to your account and accept the terms and conditions and chose the region for your new tentant.

![](images/00-2-setup-auth0-account-and-app-auth-for-genai-enabled.png)

These will help you Create a new tentant with Auth for GenAI enabled and also setup your application in the Auth0 Dashboard.

---

With these completed you are ready for [the next step](01-running-the-app.md).
