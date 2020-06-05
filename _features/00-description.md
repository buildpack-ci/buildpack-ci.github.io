---
id: description
name: Description
heading: Buildpack CI
---

Have you enjoyed the convenience that [buildpacks](https://devcenter.heroku.com/articles/buildpacks) give you when deploying on platforms that support it, such as [Heroku](https://www.heroku.com/)?  Have you wished you can have the same convenience for your CI/CD pipeline without have to dig for the steps that you need to get everything running properly?  You are probably not alone!

Buildpack CI is an action on [GitHub Actions](https://github.com/features/actions) that uses buildpacks and [Herokuish](https://github.com/gliderlabs/herokuish) to give us this convenience on the GitHub platform.  In the simplest case, adding one line to your GitHub Actions [workflow](https://help.github.com/en/actions/configuring-and-managing-workflows/configuring-a-workflow) will build and run unit tests for your app.  Ready to give it a shot?
