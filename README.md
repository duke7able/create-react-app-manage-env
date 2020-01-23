# create-react-app-manage-env
This repo will show how to manage environments when you are using thing like craco and have many environments

# package.json script hacks
This methods can work in almost any js framework with npm

# For react
for react things are managed by its own either via react-scripts or when we use things like craco, but we could use this hack to use our own environments

# Optional
You could even add environment wise keys in .env.development , .env.production and .env.test file, doing so you would need to manage keys for all three environment differently, but then you ownt need .env.example file, and you wont need to filter env via some js file. Infact you dont even need the environment name in env then, since the keys which would go would be for that environment only
