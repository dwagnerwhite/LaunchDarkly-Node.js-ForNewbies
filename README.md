# LaunchDarkly-Node.js-ForNewbies
We want users of all levels to be successful on their LaunchDarkly journey.  This simple node.js application created on Windows which will have you performing proof of concepts in no time at all!

To get started, download [Node.js](https://nodejs.org/en/download/).

# LaunchDarkly
While LaunchDarkly Feature flags are configured via the user-friendly LaunchDarkly UI, an SDK is required to enable full functionality. See the [LaunchDarkly Quickstart page](https://app.launchdarkly.com/default/test/quickstart#/).

# SDK
This repository has everything you need to configure your client side SDK. Simply clone the repository and navigate to hello-node-client using your node.js command window which was downloaded above. 
Within hello-node-client you will find an `index.js` file.
This file can be opened with Windows Notepad or Wordpad if you do not have a handy Windows vi editor.

Update LaunchDarkly Client Keys and Feature Flags to values provided to you via the LaunchDarkly UI.

```
const ldClient = LaunchDarkly.initialize('1234598791011', user);

const flagValue = ldClient.variation("your-feature", false);

```

# Ready, set, LaunchDarkly!
After replacing the values as specified above you should be able to simply type `node index.js` at the command prompt of your node.js command window within the `hello-node-client directory`.

Hopefully you will see the visual below and be on your way to LaunchDarkly!

![image](https://user-images.githubusercontent.com/79271889/168395234-2edc35ae-ce8e-4a1e-9b73-29c59d8a865a.png)


