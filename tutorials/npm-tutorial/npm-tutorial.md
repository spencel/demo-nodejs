Node Package Manager (NPM) Tutorial
=

NPM is a JavaScript package manager.


1. Create a new folder and give it a name such as *my-node-project*.
2. Navigate to the folder in a CLI.
3. Create a package.json file by execute the following command:

```
npm init
```
You will be prompted to enter a package name, which is typically the same name as the folder. You may use the default values for everything else for now.

4. Let's try using npm to get packages.
5. Get lodash by executing the command below.

```
npm i -s lodash
```
The -s flag saves lodash as a dependency for this project. If you view package.json, then you will see something like the following in part of that file:
```
"dependencies": {
    "lodash": "^4.17.15"
  }
```

6. If you want to remove lodash as a dependency, then execute the command below:

```
npm un -s lodash
```

7. If you ever download a project, then you will need to tell npm to download all of the modules listed in its package.json file by executing the following command:

```
npm i
```

Resources:
- [https://docs.npmjs.com/](https://docs.npmjs.com/)