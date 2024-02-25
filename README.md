## NotesGPT 📝

## Generate action items from your notes in seconds. Powered by Convex, Together.ai, and Whisper. 🚀

## Tech Stack 💻

Convex for the database and cloud functions
Next.js App Router for the framework
Together Inference for the LLM (Mixtral)
Together Embeddings for the embeddings for search
Convex File Storage for storing voice notes
Convex Vector search for vector search
Replicate for Whisper transcriptions
Clerk for user authentication
Tailwind CSS for styling
Deploy Your Own

## You can deploy this by setting up the following services and adding their environment variables: 🗺️

Run npm install to install dependencies.
Run npm run dev. It will prompt you to log into Convex and create a project.
It will then ask you to supply the CLERK_ISSUER_URL. To do this:
Make a Clerk account.
Copy both the CLERK_SECRET_KEY and NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY API keys into .env.local.
Do steps 1-3 here and copy the Issuer URL. It should look something like https://some-animal-123.clerk.accounts.dev.
Add CLERK_ISSUER_URL to your Convex Environment Variables (deep link also available in your terminal). Paste the Issuer URL as the value and click "Save".
Now your frontend and backend should be running and you should be able to log in but not record.
Make a Together account to get your API key.
Make a Replicate account to get your API key.
Save your environment variables in Convex as REPLICATE_API_KEY and TOGETHER_API_KEY.
