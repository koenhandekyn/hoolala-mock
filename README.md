# running the project

```bash
hugo server -D
```

# gitignore

  In a typical Hugo project, the public directory is where the static files are generated when you build the site using the hugo command. Whether or not you should track the public directory in Git depends on your deployment strategy:

1 Should Be Ignored (Common Scenario):

     If you have a deployment process that generates the site (e.g., using a CI/CD pipeline or building on a server like Netlify or Vercel), you typically do not want to commit the public directory. Instead, you would generate it as
     part of the build process. This approach ensures you have less noise in your repository and reduces the risk of committing outdated or incorrect generated files.

2 Should Be Tracked (Publication on GitHub Pages or Similar):
     In some cases, like when deploying directly to GitHub Pages, you might need to track the public directory or its contents because it's directly served as the static site. Usually, this involves using the gh-pages branch to store
     the site content rather than the main branch.

  Based on the common practice and unless you have a specific reason to track it, it's usually best to ignore the public directory. If your deployment strategy requires it, you can remove it from the .gitignore.
