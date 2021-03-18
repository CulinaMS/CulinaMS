# Culina MS

Culina MS wants superboost everyones kitchen: manage your inventory, create mealplasn, count your calorie intake. Every kitchen related workflow at one place.

## 📚 Project Definition

ColinaMS is an opinionated kitchen ERP system thats wants to be easy and pleasant to use. New users shuld be able to start within minutes and advanced users should be offered many use cases to discover. The platform should provide advanced power features to those that desire it but they should not interfere with the core simple user experience.

ColinaMS is not designed as an extensible platform to be used for purposes that differ to the statement above. Never the less ColinaMS aims to be useable as backend for other great projects providing a solid API.

In regards to development philosophy, ColinaMS has a relaxed, open & positive approach. At the end of the day this is free software developed and maintained by people donating their own free time.

## 🛣️ Road Map

ColinaMS is just starting, so we want to get the basic things done before reaching for higher goals.

Below is a high-level road map view for ColinaMS to provide a sense of direction of where the project is going. This can change at any point and does not reflect many features and improvements that will also be included as part of the journey along this road map. For more granular detail of what will be included in upcoming releases you can review the project milestones as defined in the "Release Process" section below.

- **First Shot On Database Design**
  - *Starting with an implementation for storing food items and developing onwords from there*
- **Import/Export Features**
  - *Import-/Export should be a first class citizen in ColinaMS. This way users can participate from each other and the database can be filled quicker.*
- **APIs**
  - *Implement an API for third parties to use ColinaMS as a backend. The APIs shall be compatible with [grocy](https://grocy.info/).*
- **Recipes**
  - *Adding recipes to ColinaMS.*

## 🚀 Release Versioning & Process

ColinaMS releases are each assigned a version number, such as "v0.25.2", in the format `v<phase>.<feature>.<patch>`. A change only in the `patch` number indicates a fairly minor release that mainly contains fixes and therefore is very unlikely to cause breakages upon update. A change in the `feature` number indicates a release which will generally bring new features in addition to fixes and enhancements. These releases have a small chance of introducing breaking changes upon update so it's worth checking the changelog for details. A change in the `phase` indicates a much large change in BookStack that will likely incur breakages requiring manual intervention.

## 🛠️ Development & Testing

All development on ColinaMS is currently done on the `main` branch. When it's time for a release the `main` branch is merged into release.

### 📜 Code Standards

TBD

### 🐋 Development using Docker

This repository ships with a Docker Compose configuration intended for development purposes.

## 🌎 Translations

TBD

## 🎁 Contributing, Issues & Pull Requests

Feel free to create issues to request new features or to report bugs & problems. Just please follow the template given when creating the issue.

Pull requests are welcome. Unless a small tweak or language update, It may be best to open the pull request early or create an issue for your intended change to discuss how it will fit in to the project and plan out the merge. Just because a feature request exists, or is tagged, does not mean that feature would be accepted into the core project.

Pull requests should be created from the `main` branch since they will be merged back into `main` once done. Please do not build from or request a merge into the `release` branch as this is only for publishing releases.

The project's code of conduct [can be found here](https://github.com/BookStackApp/BookStack/blob/master/.github/CODE_OF_CONDUCT.md).

## 🔒 Security

If you would like to report a security concern in a more confidential manner than via a GitHub issue, You can directly email the lead maintainer [cdrfun](https://github.com/cdrfun). You will need to login to be able to see the email address on the [GitHub profile page](https://github.com/cdrfun).

## ♿ Accessibility

We want BookStack to remain accessible to as many people as possible. We aim for at least WCAG 2.1 Level A standards where possible although we do not strictly test this upon each release. If you come across any accessibility issues please feel free to open an issue.

## 🖥️ Website, Docs & Blog

For now everything related to ColinaMS will be within this repository.

## ⚖️ License

The ColinaMS source is provided under the MIT License. The libraries used by, and included with, BookStack are provided under their own licenses.

## 👪 Attribution

ColinaMS is heavily inspired by [grocy](https://grocy.info/) and wants to stay compatible with it as long as possible.
