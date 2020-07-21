to run as executable:

on package.json:
"bin": {
    "eye": "index.js"
}

on index.js:
#!/usr/bin/env node

on terminal(project folder):
chmod +x index.js  // windows don't need this step
npm link

ready to run on terminal, just call eye(name can be changed) in the project folder, a filename must be passed as argument(eye app.js), otherwise index.js will be assumed.