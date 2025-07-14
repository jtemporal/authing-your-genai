# WIP Recap your learnings

Now that Assistant0 has the Calculator and Gmail. 🎉🎉🎉

In case you want to have some fun, here's an idea for an email draft for you to send later.

Prompt: "Hey Assistant0, can you draft an email to my friend Will (william.johnson@okta.com) to tell them I just completed the 'Authing your GenAI' workshop? Mention that now I know how tool calling works and I'm very excited to add even more features securely with Auth0 in my GenAI applications."

The expected behavior:

1. Recognize the intent to draft an email. Identify the recipient Jess and the email as well as the core message - to talk about the workshop.
1. Then Use the gmailTool with an action like draft_email.
1. Retrieve the Google access token using the Auth0 SDKs to draft the email
1. Show the drafted email in chat and ask if there's anything else they could do.

With that you learned what tool calling is, added 3 tools to your agent, and you learned how to setup Google to use the Google APIs for tool calling with Auth for GenAI.

Thank you for participating and don't forget to share what you learned and tag us!

Show us what you build by tagging us on social!
* **X** [@auth0](https://x.com/auth0)
* **LinkedIn** [Auth0](https://www.linkedin.com/company/auth0)
* **GitHub** [Auth0](https://github.com/auth0)
