# NestedNetlifyDeploymentExample

To make this repository successfully deploy on Netlify, you need to edit one property in your Netlify project's Build settings.

Go to your Netlify project's 'Continuous Deployment' settings. Your URL sould look something like this:
`https://app.netlify.com/sites/{YOUR NETLIFY WEBSITE NAME HERE}/settings/deploys#continuous-deployment`

In the "Build settings" block on the page, we want to edit the "Publish directory" so that it points to whatever nested folder is holding all of your actual website files & folders & etc.

In this repository, the website is contained in a folder named "nestedFolder".

This means my "Publish directory" must have a value of "nestedFolder".

It should look something like this to work:

![NestedNetlifySettings](.\NestedNetlifySettings.png)



Once that property has been edited & saved, enjoy your awesome deployed website!
