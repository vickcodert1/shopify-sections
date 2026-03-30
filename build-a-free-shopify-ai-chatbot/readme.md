[![a Free Shopify AI Chatbot](https://i.ytimg.com/vi/ITKH43HX718/maxresdefault.jpg)](https://youtu.be/ITKH43HX718?list=PLvT_6E7D1NZIlHa09cgswsjD9QunUpHKy)

The future of e-commerce is here, and it’s more intelligent and accessible than ever. Shopify just dropped a game-changer: the **Storefront Model Context Protocol (MCP).** This powerful tool allows you to build a sophisticated AI agent for your store that can browse your entire catalog, answer customer questions, and even add products to the cart—all automatically.

The best part? You can build and run this AI shopping assistant **completely for free.**

In this step-by-step guide, we’ll walk you through how to create and deploy your own AI agent, just like the one in the demo below.

**What Can This AI Agent Do? A Live Demo**
Before we dive into the code, let’s look at what this AI agent is capable of:

**Intelligent Product Search:** Customers can ask for products in natural language, like “What products are you selling?” or “Do you have any red color t-shirts?” The AI will search your catalog and return products with images, prices, and descriptions.
**Seamless Cart Management:** The agent can add specific products and variants directly to the customer’s cart.
**Multi-Language Support:** Impressively, the AI can interact with customers in their native language, as demonstrated with Urdu in the video, making your store accessible to a global audience.
**24/7 Customer Service:** This agent works around the clock to assist visitors, answer queries, and guide them to purchase.
Now, let’s build it!

# Step-by-Step Tutorial: Building Your Shopify AI Agent
**Prerequisites:**
Before you start, make sure you have the following:

A **Shopify Partner Account** (free to sign up).
A **Shopify Development Store** (you can create one through your Partner dashboard).
A **Claude API Key** (You can also use OpenAI or Gemini. We’ll use Claude for this guide. Sign up at console.anthropic.com).
**Node.js** and npm installed on your computer.
A code editor like **VS Code.**

# Step 1: Clone the Repository and Install Dependencies
We’ll be using a pre-built project from Shopify that simplifies the process.

Open your terminal (or VS Code’s integrated terminal).
Run the following command to clone the GitHub repository: git clone https://github.com/Shopify/shopify-app-template-react cd shopify-app-template-react
Next, install the necessary project dependencies using npm: npm install Note: You might see some vulnerability warnings. You can ignore them for this tutorial.

# Step 2: Set Up Your API Key
The AI needs an API key to access the language model (Claude).

In your project folder, you should see a file named .env.example. Open it in your code editor.
You need to create a new file by renaming this one. Delete the .example part so the file is just called .env.
Open the .env file and find the line for the API key. It will look like:
CLAUDE_API_KEY=your_claude_api_key_here
Go to your Claude API console, create a new API key, and copy it.
Paste your API key into the .env file, replacing your_claude_api_key_here.
Save the file.

# Step 3: Install Shopify CLI and Create Your App
Now, we’ll connect our code to your Shopify store.

In your terminal, ensure you are in the project directory and install the Shopify CLI:
bash npm run shopify app install
The CLI will guide you through the setup:
**Select a partner profile:** Choose your organization.
Create a new app or use existing? Select “Create it as a new app.”
**Your app’s name:** Enter a name, e.g., My AI Shopping Agent.
**Configuration file name**: Press Enter to accept the default.
**Select a development store:** Choose the development store you want to install the app on.
The CLI will now generate your app and handle the configuration. Once it’s done, it will provide a local URL (like ngrok URL) to preview your app.

# Step 4: Install and Enable the App on Your Store
The CLI will prompt you to open your app. Press E to open it in your browser.
You’ll see the installation screen for your new app. Click “Install” to add it to your development store.
**Crucial Step:** After installation, you must enable the app embed in your theme.
Go to your Shopify admin dashboard.
Navigate to **Online Store > Themes.**
Click **Customize** on your active theme.
In the theme editor, look for the **App Embed** section in the settings.
Find your “AI Chat Assistant” app and make sure it is **enabled.**
Click **Save.**

# Step 5: Test Your Live AI Assistant!
The moment of truth! Let’s see your AI agent in action.

Open the preview of your store by clicking the “View” button in your theme editor.
You should now see the AI chatbot icon (usually a chat bubble) on your storefront.
**Test it out:**
Try: “What products do you sell?”
Try: “Do you have a brown t-shirt?” and then “Add it to my cart in size small.”
If you have international customers, try interacting in another language!
Congratulations! You have successfully built and deployed a powerful AI shopping assistant for your Shopify store.

# Conclusion:
Shopify’s Storefront MCP is a revolutionary step towards AI-native e-commerce. By following this guide, you’ve equipped your store with a tool that can significantly enhance customer experience and potentially boost sales, all without a monthly subscription fee.

This technology is evolving rapidly. To stay ahead of the curve, subscribe to our channel for more tutorials like this.

**Want to take it further?** If this post gets enough positive feedback, we’ll create a follow-up guide on how to fully deploy this app to a live server so it runs 24/7 without needing your local computer.

**Ready to start your Shopify journey?** Use our link below to sign up for a Shopify plan and get started for just $1/month!

**Boost Your Sales with Volume Discounts:** Check out our app, Big Bulk Discount, to easily add tiered pricing and increase your average order value. It comes with a 7-day free trial!
