# react-quick-start

## Step1 - Project creation
- Create a codespace on github - (dont need to install vscode and node locally)
- Chat GPT helping a lot
- npx create-next-app nome-do-seu-projeto (or ./ to create on current folder)
- npm run dev
- delete page content and start from scratch

## Step2 - Deploy
- Buid your app, npm run build
- 

## Lessons learned
- Never define a component inside another component!
- Deployed folder is .next, we can change it in next config file
- Managing state:
1) Identify your component’s different visual states
1) Determine what triggers those state changes
1) Represent the state in memory using useState
1) Remove any non-essential state variables
1) Connect the event handlers to set the state
