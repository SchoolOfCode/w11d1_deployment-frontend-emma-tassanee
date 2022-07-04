## Deploy a React SPA (single page application) on Netlify

1. Have a look through the Netlify documentation:
 - https://docs.netlify.com/
 - Find any Netlify resources/videos
 
Practice taking turns to explain the answers to these questions:
 - What is Netlify?
 - What problems does Netlify solve?
 - When would you use it?
 - When would you not use it?
 - What are some alternatives/competitors to Netlify? (Just to know what else is out there.)

2. Initialise your React app with Create React App. 
 - It can just be the standard "Hello World" boilerplate.
 - When you deploy your app to Netlify, Netlify will assume your React project is at the root of your repository. If it's not, you can still deploy but it'll take extra configuration. Have a google for how you can have the Create React App command not initialise the project in a subfolder (as it normally does).

3. Get it deployed to Netlify by following this documentation: https://docs.netlify.com/integrations/frameworks/create-react-app/#app.
 - You'll need to sign up for a Netlify account.
 - Ensure that it's configured for automatic deployment (so that every time you push to GitHub, Netlify automatically rebuilds and redeploys your app).
 - You should be able to access your deployed app via a public URL that Netlify has given you.
 - Bonus: Change the public URL to something more meaningful/personalised.

4. Make a meaningful change to the app (commit and push to git) and ensure that automatic deployment has worked (troubleshoot if not).
 - You should see your changes appear at the public URL (after a few minutes).

5. Bonus: Research Netlify docs/ecosystem (for things like how to configure environment variables, etc.)
6. Bonus: Research Netlify edge functions, analytics, forms, identity, etc.
