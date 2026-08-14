🤖 Google AI GitHub Mobile Studio
A lightweight, mobile-first AI Assistant powered by Google Gemini 2.5 Flash and integrated directly with the GitHub REST API. This app allows you to manage, create, edit, and inspect your GitHub repositories using natural language prompts from your smartphone or desktop.
✨ Features
￼ 🚀 Autonomous GitHub Actions (Tool Calling):
￼ Create Repositories: Ask the bot to create public or private repositories.
￼ Create & Edit Files: Write new code, edit existing scripts, or update README files with automatic commits.
￼ Read Codebase: Inspect files, analyze logic, and ask Gemini to debug or refactor existing code.
￼ Directory Browsing: View folder structures and file listings across your repos.
￼ Delete Files: Remove outdated code or temporary files on demand.
￼ 📱 Mobile-Optimized Experience:
￼ Persistent Authentication: Saves your GitHub Personal Access Token (⁠ghp_...⁠) locally in your browser so you don't have to log in every time.
￼ Persistent Chat History: Automatically saves your conversation on your device across refreshes.
￼ Fullscreen Toggle: Standalone web app mode for an immersive mobile view.
￼ Touch-Friendly UI: Designed specifically for quick navigation on mobile screens.
🛠️ Quick Setup & Deployment
Step 1: Deploy to GitHub Pages (Free)
1. Create a new public repository on GitHub (e.g., ⁠ai-bot⁠).
2. Upload the ⁠index.html⁠ file to the root of your repository.
3. Go to Settings > Pages in your repository.
4. Under Source, select ⁠Deploy from a branch⁠.
5. Under Branch, select ⁠main⁠ (or ⁠master⁠) ⁠/root⁠, and tap Save.
6. Wait a minute for GitHub to build your page. You will get a link like:
⁠https://<your-username>.github.io/<repository-name>/⁠
Step 2: Generate a GitHub Personal Access Token (PAT)
1. On GitHub, go to Settings > Developer Settings > Personal Access Tokens > Tokens (classic).
2. Click Generate new token (classic).
3. Give it a name (e.g., ⁠Google AI Bot⁠).
4. Select an expiration date (e.g., No expiration or 30 days).
5. Check the ⁠repo⁠ checkbox scope (this gives the bot permission to read, write, and create repositories).
6. Click Generate token and copy the string starting with ⁠ghp_...⁠.
Step 3: Connect & Use
1. Open your hosted GitHub Pages site on your phone or computer.
2. Tap the Settings icon (Sliders) at the top left.
3. Paste your token into the Personal Access Token field and click Connect & Save.
4. You're ready! Start giving the AI instructions.
💡 Example Prompts to Try
￼ "Create a new public repository named ⁠my-express-api⁠."
￼ "Add an ⁠index.js⁠ file to my repo ⁠my-express-api⁠ with a basic Hello World server."
￼ "Read ⁠README.md⁠ in my active repository and improve its formatting."
￼ "List all the files inside my repository ⁠my-web-app⁠."
🔒 Security Notice
￼ Your Personal Access Token is stored strictly inside your own device's browser ⁠localStorage⁠.
￼ No servers or third parties store your GitHub token.
￼ Keep your token private. If you ever suspect it has been compromised, revoke it immediately via GitHub settings.
📄 License
Distributed under the MIT License. Feel free to modify and adapt for your own workflows!
