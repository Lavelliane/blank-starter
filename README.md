**Prerequisites:**

- **Node.js (v18.x or v20.x):** [https://nodejs.org/en/download/package-manager](https://nodejs.org/en/download/package-manager) (Ensure you have an LTS version for stability)
- **Yarn (package manager):** [https://classic.yarnpkg.com/lang/en/docs/install/](https://classic.yarnpkg.com/lang/en/docs/install/) (If not already installed, run `npm install -g yarn` in your terminal)
- **Code Editor:** Choose your preferred editor like Visual Studio Code, WebStorm, or Atom.

**Optional VSCode Extensions (Enhance Development Experience):**

1. **GraphQL:** Improves GraphQL syntax highlighting and autocompletion.
2. **ES7+ React/Redux/React-Native snippets:** Speeds up coding with pre-written code snippets for modern JavaScript features and React patterns.
3. **Tailwind CSS Intellisense:** Provides intelligent code completion and suggestions for Tailwind CSS classes.
4. **Prettier:** Auto-formats your code for consistent formatting and readability.
5. **Auto Close Tag and Auto Rename Tag:** Auto-formats your code for closing and renaming tags in JSX.

**Steps:**

1. **Create Project Directory:**

   ```bash
   mkdir my-strapi-nextjs-app
   cd my-strapi-nextjs-app
   ```

2. **Install Strapi CMS:**

   ```bash
   npx create-strapi-app@latest my-cms-app
   ```

   - Replace `my-cms-app` with your desired application name.
   - This command creates a new Strapi project with the specified name and installs the necessary dependencies.

3. **Start Strapi Development Server:**

   - Navigate to the Strapi project directory:

     ```bash
     cd my-cms-app
     ```

   - Start the Strapi development server:

     ```bash
     npm run develop
     ```

   - Open `http://localhost:1337/admin` in your web browser to access the Strapi admin panel. You'll need to create an admin user to manage your content.

4. **Create Next.js Application:**

   - Navigate back to the main project directory:

     ```bash
     cd ..
     ```

   - Create a new Next.js application by forking or cloning this repository:

     ```bash
     git clone https://github.com/Lavelliane/blank-starter.git
     ```
      ***Install Dependencies***
     ```bash
     npm install
     ```

   - This command generates a basic Next.js project structure with the dependencies for Apollo GraphQL.


