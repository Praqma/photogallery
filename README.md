# Photo Gallery

This repository is hosted as http://code.praqma.net/photogallery and is used to generate json for our website photo carousels.
The user browsing the website is giving a few inputs, and if that user is logged in with Google access to to the chosen Google Photo Album we generate json.

Save the json and commit it to the relevant website.

## Howto

[User guide - should explain how to use this hosted utility, like where to go, who to login as, what to type in the input fields, how to find those valus, and what to do from when the json is generated]

## Other documentation


## Roadmap

Given the history below, we actually find that this approach might have more value in the long run. Despite the user have to authenticate as a another user and generate json content to be saved and committed to another repository, there are some benefits. For example we could extend the UI of this generator to ask the user is she wants background color, captions, or change other parameters.

It will be in future versions.


## History

This repository is created to work around credentials and authorization issues found in https://github.com/Praqma/code-conf.com/issues/657 about implementing carousel photo gallery for our websites.
The problem is anonymous access to the deprecated public albums from Picasa not available in Google Photos.

We couldn't find a solution that was reasonable regaring oauth for the photos, not even with read-only access tokens: https://github.com/Praqma/code-conf.com/issues/813

Alternatively we took the approach of hosting this litte website that can use the browser sessions to generate the content (json): 	https://github.com/Praqma/code-conf.com/issues/814
