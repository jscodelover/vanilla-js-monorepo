# Workspace

- Package define in the workspace, allow you to define multiple packages within a single root package.
- With this configuration, every folder inside /packages with a package.json file is considered a local package.

- When you run npm install in the root directory, folders within packages/ are symlinked to the node_modules folder.

### installation
- mention the packages inside the project in which it is need. Workspace automatically create a symlink for those common package in the root node_modules when we run (npm | pnpm | yarn)install.