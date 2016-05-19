
#My goal is to make automated process of generating APK file and published it to Play store. 

Now a days it is time consuming thing to generate apk file by updating version name and version code everytime and published APK file to play store. Even it is always hard to remember version code and version name for each code that use for distribution.

As per best practice, version name and version code should be based on the code, that we have commited on any repository (e.g. gitHub). So, to make this process automated, I have planed to make it on every commit of code.

You can upload your app to Google Play Store with following 4 steps only.

1. Update code as per your requirement/update/bug-fixing (If required)
2. Commit code to your gitHub repository
3. Apply tag to your commit


# Requirements

You must need following environment to make this process automated

1. Project to publish
2. Github account
3. CI (Continues Integration) framework
4. Google Play Store account


## Code Example

Following are the changes you need to do in your existing project.

You need to update gradle in such way that it takes highest apply tag as version code and version name. I believe that is only required for release version of the app. So it is required to update for release version of the flavour only.





## Motivation

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Installation

Provide code examples and explanations of how to get the project.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)
