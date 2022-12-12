[![Open in GitPod](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/EddieHubCommunity/LinkFree) ![Uptime](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FEddieHubCommunity%2Fmonitoring%2Fmaster%2Fapi%2Flink-free%2Fuptime.json) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/EddieHubCommunity/LinkFree) ![GitHub repo size](https://img.shields.io/github/repo-size/EddieHubCommunity/LinkFree)

> ### A note for Hacktoberfest participants:
>
> - Pull requests which add or edit your information in a `data/${yourname}.json` file will NOT be counted for Hacktoberfest.
> - Pull requests which improve the codebase, documentation, or other aspects of the project and are in line with the core values of the event will count. The project contains the `hacktoberfest` topic, so the PRs will be automatically counted towards Hacktoberfest. However, profile update PRs will have the label `invalid` and therefore won't be counted towards this event.

# LinkFree by EddieHub

- LinkFree connects audiences to all of your content with one link. It is an **Open Source** alternative to _Linktree_ implemented in JavaScript using NextJS, Tailwind and MongoDB.
- It was initially created on a YouTube [live stream](https://www.youtube.com/watch?v=Jorl_vcp-Ew).

![Eddie Jaoude's LinkFree profile GIF](https://user-images.githubusercontent.com/106697681/176986263-b8c278f1-41a8-4b85-80e6-be46e9cc9a00.gif)

## 👨‍💻 Demo

Example profile for [Eddie Jaoude](https://linkfree.eddiehub.io/eddiejaoude)

## 👇 Prerequisites

You can use [Gitpod in the cloud for free](https://gitpod.io/#https://github.com/EddieHubCommunity/LinkFree) or you can set this up locally with the following steps.

Before contributing or adding a new feature, please make sure you have already installed the following tools:

- [Git](https://git-scm.com/downloads)
- [NodeJs](https://nodejs.org/en/download/)

## QUICKSTART

1. copy the `.env.example` file to `.env` and update any details required
1. mongodb is required, it is possible to use `docker-compose up` to start the mongodb service
1. `npm install`
1. `npm run dev`

## 👨‍💻 Contributing

- Contributions make the open source community such an amazing place to learn, inspire, and create.
- Any contributions you make are **truly appreciated**.
- Check out our [contribution guidelines](./docs/contributing/CONTRIBUTING.md) for more information.

## 🎭 To Add Your Profile

In the `data` directory, create a `.json` file with the same name as your GitHub username. For example, if your GitHub username is `eddiehub`, create a file named `eddiehub.json`. This will ensure that your username is unique. 

**Optional fields: `milestones` and `type(personal | community)`**\
Looking for inspiration? You can view the following profiles for an example:

- [Eddie Jaoude](https://github.com/EddieHubCommunity/LinkFree/blob/main/data/eddiejaoude.json)
- [Naomi Carrigan](https://github.com/EddieHubCommunity/LinkFree/blob/main/data/nhcarrigan.json)
- [Kaiwalya Koparkar](https://github.com/EddieHubCommunity/LinkFree/blob/main/data/kaiwalyakoparkar.json)

Your brand new file should look something similar to this one:

> **Note**: add/remove `links` objects to customise your profile, `milestones` are optional

```json
{
  "name": "YOUR NAME",
  "displayStatsPublic": true,
  "type": "personal",
  "bio": "Open Source Enthusiast!",
  "avatar": "https://github.com/YOUR_GITHUB_USERNAME.png",
  "tags": ["javascript", "typescript"],
  "socials": [
    { "platform": "twitter", "url": "https://twitter.com/YOUR_TWITTER_USERNAME" },
    { "platform": "github", "url": "https://github.com/YOUR_GITHUB_USERNAME" }
  ],
  "links": [
    {
      "name": "Follow me on GitHub",
      "url": "https://github.com/YOUR_GITHUB_USERNAME",
      "icon": "github"
    },
    {
      "name": "Follow me on Twitter",
      "url": "https://twitter.com/YOUR_TWITTER_USERNAME",
      "icon": "twitter"
    }
  ],
  "milestones": [
    {
      "title": "Started Freelancing",
      "date": "December 2021",
      "icon": "dollar",
      "color": "grey",
      "description": "Started freelancing",
      "url": "https://www.eddiejaoude.io/"
    }
  ]
}
```

Your URL will be `https://linkfree.eddiehub.io/<yourusername>`

For example: <https://linkfree.eddiehub.io/eddiejaoude>

To include your `avatar`, you have to replace `<yourusername>` with your **GitHub username** in the format of `https://github.com/<yourusername>.png` and it will automatically be fetched from your GitHub account.

For example: <http://github.com/eddiejaoude.png>

Note: After your PR gets merged, the project still needs to be deployed for your profile to be displayed.

### Available Icons:

Check [Icons.md](/icons.md) for all the supported icons.

### Single user mode

If you wish to self-host this app for a single user, follow the same steps as above, but then in the file `config/user.json` add your username.

For example

```json
{
  "username": "eddiejaoude"
}
```

## 🛡️ License

LinkFree is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💪 Thanks to all Contributors

Thanks a lot for spending your time helping LinkFree grow. Thanks a lot! Keep rocking 🍻

[![Contributors](https://contrib.rocks/image?repo=EddieHubCommunity/LinkFree)](https://github.com/EddieHubCommunity/LinkFree/graphs/contributors)

## 🙏 Support

This project needs a ⭐️ from you. Don't forget to leave a star ⭐️
