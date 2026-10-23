# CircleAssist FAQ

[简体中文](FAQ.zh-Hans.md) · [Back to CircleAssist](../README.md)

## Which Macs are supported

Apple Silicon Macs with macOS 26 or later. The current device baseline is 16 GB RAM. The memory needed for a local AI model depends on the model; 16 GB does not support every available model.

## What do I need before my first task

Follow the welcome conversation in order: sign in to CircleAssist with an email verification code, download the approximately 539 MB local speech model, and configure a cloud AI provider or a supported local model. Signing in to CircleAssist and connecting an AI model are separate steps; the app account does not include a cloud provider API key.

## Is cloud AI usage included

Third-party provider fees are separate. App access follows the current offer on the [official website](https://quanzhu.fangtangtech.com/en). Desktop tasks may use multiple model calls for planning, actions, recovery, and verification. Input usage includes context and tool information, not just the sentence you typed.

## Can the app use AI in the background

Yes. When proactive suggestions are enabled and qualifying events occur, the app can request the configured model without a new chat message. Turn proactive suggestions off in settings if you do not want these requests. Voice recognition alone uses the local speech pipeline; optional voice-input AI refinement is a separate model operation.

## Does local speech recognition mean everything stays offline

Speech recognition runs locally after setup. Cloud AI receives the task text and relevant images you submit. Cloud AI refinement sends recognized voice-input text to the selected provider. Online searches and account services also require a connection. Read the [privacy information](https://quanzhu.fangtangtech.com/en/privacy) before choosing a provider.

## Why does a feature need a macOS permission

Microphone access supports voice input. Accessibility supports relevant text insertion and desktop actions. Screen permissions support features that read or capture the screen. Grant the permissions requested by the feature you use, then follow its retry instructions.

## Does dictation or computer control work in every application

Compatibility varies by application and input field. Protected fields or controls that do not expose the necessary system interfaces may not work. Image tasks require an image-capable model. When reporting a problem, include the target application and the operation that failed.

## Which file should I download

Use the Mac DMG from the official website or a published CircleAssist Release. GitHub's automatically generated Source code (zip / tar.gz) archives contain only product documents, images, and feedback templates from this repository. They contain neither the application's source code nor an installable application. Open the DMG and drag the app into Applications.

## How do updates work

Use Check for Updates in the app. The app's update service continues to use the official website. GitHub Releases provide release notes and an additional manual download when assets are available.

## How do I report a problem privately

Email [support@fangtangtech.com](mailto:support@fangtangtech.com). Public [issue forms](https://github.com/zipshuo-cloud/circleassist/issues/new/choose) are for reports without private data. Include the app version, macOS version, device, and reproduction steps. Do not include credentials, verification codes, or full conversations.
