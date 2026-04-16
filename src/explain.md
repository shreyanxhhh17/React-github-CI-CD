React-> Manual code push...test...build...deploy...repeat

What is Github Actions?
GitHub Actions is a powerful CI/CD platform that allows you to automate your software development workflows directly from your GitHub repository. With GitHub Actions, you can create custom workflows that build, test, and deploy your code whenever a specific event occurs in your repository, such as a push or pull request.

Why use GitHub Actions for React projects?
1. Seamless Integration: GitHub Actions is tightly integrated with GitHub, making it easy to set up and manage your CI/CD pipelines without needing to leave your repository.
2. Customizable Workflows: You can create custom workflows that fit your specific needs, whether it's running tests, building your React application, or deploying it to a hosting service.
3. Community Support: GitHub Actions has a large and active community, which means you can find a wide variety of pre-built actions and workflows that can help you get started quickly.
4. Cost-Effective: GitHub Actions offers free minutes for public repositories and a generous amount

CI/CD:
CI - Continuous Integration is the practice of automatically integrating code changes from multiple contributors into a shared repository several times a day. The main goal of CI is to detect and fix integration issues early, ensuring that the codebase remains stable and functional.

Jab bhi developer code push kare toh:
dependencies install
build
test

CD: Build hone k baad app automaticalll deploy ho jata hai.


Simple Pipleine:
1. Code push
2. Install dependencies
3. Build
4. Test
5. Deploy

Vercel vs Github Actions:
Vercel is a cloud platform for static sites and serverless functions that provides a seamless deployment experience for frontend applications, including React. It offers features like automatic deployments, preview URLs, and built-in CDN.
GitHub Actions, on the other hand, is a general-purpose CI/CD platform that can be used to automate a wide range of tasks beyond just deployment. It allows you to create custom workflows for building, testing, and deploying your applications, and it integrates directly with your GitHub repository.