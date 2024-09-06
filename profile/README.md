# ConfigCat Feature Flags

[ConfigCat is a hosted feature flag and configuration management service](https://configcat.com/) that lets you separate releases from deployments. You can turn your features ON/OFF using ConfigCat Dashboard even after they are deployed. ConfigCat lets you target specific groups of users based on region, email or any other custom user attribute. Manage feature toggles across frontend, backend, mobile, desktop apps.

## 🔥 How does ConfigCat work?
- You set your feature flags on the ConfigCat Dashboard.
- Your feature flags get distributed across the ConfigCat CDN.
- The ConfigCat SDK in your application downloads and evaluates the feature flags.

Read more about the [ConfigCat components and architecture.](https://configcat.com/architecture/)

![Architecture](https://github.com/configcat/.github/blob/master/profile/architecture.jpg)

##  🤓 Get started with ConfigCat
- Website: https://configcat.com/
- Dashboard: https://app.configcat.com/
- API: https://api.configcat.com/docs/
- Docs: https://configcat.com/docs/
- Blog: https://configcat.com/blog/

## 💸 Plans & Pricing
[See Pricing](https://configcat.com/pricing/)

## 🚀 Open-source SDKs
The purpose of the SDKs are to download, cache feature flag values and to evaluate targeting rules. All SDKs provide a simple interface to access your feature flags from your application.

| SDK  |      |      |
| ---- | ---- | ---- |
| .NET | [Documentation](https://configcat.com/docs/sdk-reference/dotnet/) | [Source code](https://github.com/configcat/.net-sdk) |
| Android (Java) | [Documentation](https://configcat.com/docs/sdk-reference/android/) | [Source code](https://github.com/configcat/android-sdk) |
| C++ | [Documentation](https://configcat.com/docs/sdk-reference/cpp/) | [Source code](https://github.com/configcat/cpp-sdk) |
| Dart (Flutter) | [Documentation](https://configcat.com/docs/sdk-reference/dart/) | [Source code](https://github.com/configcat/dart-sdk) |
| Elixir | [Documentation](https://configcat.com/docs/sdk-reference/elixir/) | [Source code](https://github.com/configcat/elixir-sdk) |
| Go | [Documentation](https://configcat.com/docs/sdk-reference/go/) | [Source code](https://github.com/configcat/go-sdk) |
| Java | [Documentation](https://configcat.com/docs/sdk-reference/java/) | [Source code](https://github.com/configcat/java-sdk) |
| JavaScript (Browser) | [Documentation](https://configcat.com/docs/sdk-reference/js/) | [Source code](https://github.com/configcat/js-sdk) |
| JavaScript (React) | [Documentation](https://configcat.com/docs/sdk-reference/react/) | [Source code](https://github.com/configcat/react-sdk) |
| JavaScript (Server-Side Rendered - SSR)| [Documentation](https://configcat.com/docs/sdk-reference/js-ssr/) | [Source code](https://github.com/configcat/js-ssr-sdk) |
| Kotlin Multiplatform | [Documentation](https://configcat.com/docs/sdk-reference/kotlin/) | [Source code](https://github.com/configcat/kotlin-sdk) |
| Node.js | [Documentation](https://configcat.com/docs/sdk-reference/node/) | [Source code](https://github.com/configcat/node-sdk) |
| PHP | [Documentation](https://configcat.com/docs/sdk-reference/php/) | [Source code](https://github.com/configcat/php-sdk) |
| Python | [Documentation](https://configcat.com/docs/sdk-reference/python/) | [Source code](https://github.com/configcat/python-sdk) |
| Ruby | [Documentation](https://configcat.com/docs/sdk-reference/ruby/) | [Source code](https://github.com/configcat/ruby-sdk) |
| Rust | [Documentation](https://configcat.com/docs/sdk-reference/rust/) | [Source code](https://github.com/configcat/rust-sdk) |
| Swift (iOS) | [Documentation](https://configcat.com/docs/sdk-reference/ios/) | [Source code](https://github.com/configcat/swift-sdk) |
| Unreal Engine | [Documentation](https://configcat.com/docs/sdk-reference/unreal/) | [Source code](https://github.com/configcat/unreal-engine-sdk) |

### OpenFeature Providers
[OpenFeature](https://openfeature.dev/docs/reference/intro) is an open specification that provides a vendor-agnostic, community-driven API for feature flagging. ConfigCat offers providers for the following platforms supported by OpenFeature SDKs.

| Provider  |      |      |
| --------- | ---- | ---- |
| .NET | [Documentation](https://configcat.com/docs/sdk-reference/openfeature/dotnet/) | [Source code](https://github.com/open-feature/dotnet-sdk-contrib/tree/main/src/OpenFeature.Contrib.Providers.ConfigCat) |
| Go | [Documentation](https://configcat.com/docs/sdk-reference/openfeature/go/) | [Source code](https://github.com/open-feature/go-sdk-contrib/tree/main/providers/configcat) |
| Java | [Documentation](https://configcat.com/docs/sdk-reference/openfeature/java/) | [Source code](https://github.com/open-feature/java-sdk-contrib/tree/main/providers/configcat) |
| JavaScript | [Documentation](https://configcat.com/docs/sdk-reference/openfeature/js/) | [Source code](https://github.com/open-feature/js-sdk-contrib/tree/main/libs/providers/config-cat-web) |
| Node.js | [Documentation](https://configcat.com/docs/sdk-reference/openfeature/node/) | [Source code](https://github.com/open-feature/js-sdk-contrib/tree/main/libs/providers/config-cat) |
| PHP | [Documentation](https://configcat.com/docs/sdk-reference/openfeature/php/) | [Source code](https://github.com/configcat/openfeature-php) |
| Python | [Documentation](https://configcat.com/docs/sdk-reference/openfeature/python/) | [Source code](https://github.com/configcat/openfeature-python) |
| Rust | [Documentation](https://configcat.com/docs/sdk-reference/openfeature/rust/) | [Source code](https://github.com/configcat/openfeature-rust) |

## 👯 Integrations
Integrate ConfigCat with your technology stack and leverage all the benefits of Feature flags within your workflows.
- [Amplitude](https://configcat.com/docs/integrations/amplitude/) - Add feature flag changes to your charts, send feature flag 
- [Bitbucket Pipe](https://configcat.com/docs/integrations/bitbucket/) - Scan source code for feature flags
- [Bitrise Step](https://configcat.com/docs/integrations/bitrise/) - Scan source code for feature flags
- [CircleCI Orb](https://configcat.com/docs/integrations/circleci/) - Scan source code for feature flags
- [Datadog](https://configcat.com/docs/integrations/datadog/) - Send feature flag change events to your monitors
- [GitHub Action](https://configcat.com/docs/integrations/github/) - Scan source code for feature flags
- [Google Analytics](https://configcat.com/docs/integrations/google-analytics/) - Send feature flag evaluation analytics
- [Jira Cloud Plugin](https://configcat.com/docs/integrations/jira/) - Manage feature flags right from Jira
- [Mixpanel](https://configcat.com/docs/integrations/mixpanel/) - Add feature flag changes to your charts, send feature flag evaluation analytics
- [monday.com](https://configcat.com/docs/integrations/monday/) - Manage feature flags right from your monday.com board
- [Slack](https://configcat.com/docs/integrations/slack/) - Get notified when a feature flag changes
- [Terraform](https://configcat.com/docs/integrations/terraform/) - Manage feature flags directly from HCL scriptsevaluation analytics
- [Trello Power-Up](https://configcat.com/docs/integrations/trello/) - Manage feature flags right from your Trello board
- [Twilio Segment](https://configcat.com/docs/integrations/segment/) - Add feature flag changes to your charts, send feature flag evaluation analytics
- [Visual Studio Code](https://configcat.com/docs/integrations/vscode/) - Manage feature flags right from your VSCode editor
- [Zapier Zap](https://configcat.com/docs/integrations/zapier/) - Build workflows based on feature flags
- [Zoho Flow](https://configcat.com/docs/integrations/zoho-flow/) - Automate tasks and build feature flag based workflows

## 💁🏼 Contributing
Feedback and contribution are welcome. [See contribution guide](https://github.com/configcat/.github/blob/master/CONTRIBUTING.md).

## ☎️ Help & Support
- [FAQ](https://configcat.com/docs/faq/) - Frequently Asked Questions
- [Contact us](https://configcat.com/support/)


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
