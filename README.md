## A GPT-3 ❤️ Nextjs Quick starter
GPT-3 Powered application using NextJS and vscode.
## QuickStart

1. Clone this repo
2. Add your OpenAI API key to .env file (sign up at https://beta.openai.com for account / key)
3. Install node_modules by running `npm install` or `yarn install` in terminal
4. In `pages/api/openai.js` you construct your request to OpenAI API
5. In `pages/index.js` you tweak your UI/UX
6. start the dev server with `yarn dev` or `npm run dev` command

## For more information on application,checkout
https://lablab.ai/t/gpt3

## Tips

If you don't have a setup on your computer that allow to run code locally, then use https://replit.com/

---

### Deployment
this application was deployed to Vercel(creators of the next.js)
Process
npm install -g vercel
vercel env add OPENAI_API_KEY (likely to bring an error but follow the process)
vercel (follow the prompt)
vercel --prod



