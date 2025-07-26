<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="left">


# NEXUX-MOBILE-FOR-ETH-GLOBAL-2024

<em></em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">
<img src="https://img.shields.io/badge/Swift-F05138.svg?style=flat&logo=Swift&logoColor=white" alt="Swift">
<img src="https://img.shields.io/badge/Gradle-02303A.svg?style=flat&logo=Gradle&logoColor=white" alt="Gradle">
<img src="https://img.shields.io/badge/Dart-0175C2.svg?style=flat&logo=Dart&logoColor=white" alt="Dart">
<img src="https://img.shields.io/badge/C++-00599C.svg?style=flat&logo=C++&logoColor=white" alt="C++">
<br>
<img src="https://img.shields.io/badge/XML-005FAD.svg?style=flat&logo=XML&logoColor=white" alt="XML">
<img src="https://img.shields.io/badge/Flutter-02569B.svg?style=flat&logo=Flutter&logoColor=white" alt="Flutter">
<img src="https://img.shields.io/badge/CMake-064F8C.svg?style=flat&logo=CMake&logoColor=white" alt="CMake">
<img src="https://img.shields.io/badge/Kotlin-7F52FF.svg?style=flat&logo=Kotlin&logoColor=white" alt="Kotlin">
<img src="https://img.shields.io/badge/YAML-CB171E.svg?style=flat&logo=YAML&logoColor=white" alt="YAML">

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)
- [Features](#features)
- [Project Structure](#project-structure)
    - [Project Index](#project-index)

---

## Overview

Nexux-mobile-for-ETH-Global-2024 is a versatile Flutter-based development framework tailored for building decentralized web and blockchain applications across multiple platforms. It integrates user authentication, wallet management, and blockchain interactions into a seamless experience for developers targeting iOS, Android, Web, Windows, macOS, and Linux.

**Why Nexux-mobile-for-ETH-Global-2024?**

This project simplifies the creation of secure, multi-platform Web3 apps with a focus on user onboarding, transaction signing, and asset management. The core features include:

- 🎯 **🌐 Cross-Platform Compatibility:** Supports mobile, web, and desktop environments for broad reach.
- 🔐 **🛡️ Secure Authentication & Wallets:** Integrates social login, email, and private key management via Web3Auth.
- 💹 **📊 Blockchain & Market Data:** Provides real-time crypto and stock market insights.
- 🔄 **⚙️ Asset Swapping & Transactions:** Facilitates seamless crypto swaps and stock purchases.
- 🚀 **🧱 Modular & Extensible Architecture:** Designed for maintainability and future feature integration.
- 🎨 **🎯 Focus on User Experience:** Ensures smooth, secure, and intuitive interactions across platforms.

---

Nexus Mobile Application: Documentation 📱
About the Application: Nexus is a Flutter-based mobile application designed to offer a seamless and secure entry point into the Web3 ecosystem. It prioritizes user experience by simplifying authentication through various social providers and direct email login, while also providing robust wallet management capabilities. The app aims to make Web3 interaction accessible to a wider audience.

Key Technologies Integrated 🛠️:

Flutter: The entire application is built using the Flutter framework, ensuring a consistent and high-performance user experience across both iOS and Android platforms from a single codebase.
Web3Auth Flutter: This is the core technology for enabling secure, non-custodial authentication and wallet management. It allows users to log in using their existing social accounts or email, and securely access their blockchain wallets.
Social Logins: Supports authentication via Google 🌐, GitHub 🐙, and Discord 👾, leveraging web3auth_flutter for seamless integration.
Email Passwordless Login: Allows users to sign in using their email address, receiving a magic link or code to authenticate.
Wallet Services: Integrates with wallet services to allow users to launch their wallets, sign transactions, and manage their blockchain assets.
Private Key Management: Securely stores user private keys (likely via shared_preferences for persistence), enabling wallet operations.
GetX: Used for state management, providing an efficient and declarative way to manage the application's state and UI updates.
Shared Preferences: Utilized for storing small amounts of persistent data locally, such as user authentication tokens or private keys, ensuring a seamless return for logged-in users.
Web3dart: A Dart library for interacting with Ethereum-compatible blockchains. It's used here for:
Address Derivation: Deriving the user's Ethereum wallet address from their private key.
Transaction Signing: Facilitating the signing of messages or transactions using the user's wallet.
HTTP: For making network requests, likely to the RPC endpoint for interacting with the blockchain or potentially for fetching user profile data.
Cupertino Icons & Material Icons: Utilizes Flutter's built-in icon libraries to provide a native look and feel for UI elements.
Custom UI Components: Features custom widgets like LoginScreen, CustomTextField, CustomButtonWidget, and SocialButtonWidget to create a unique and branded user interface with shader effects for visual flair.
Core Functionalities 🚀:

Authentication:

Users can choose to log in via Google 📧, GitHub 🐙, Discord 👾, or a passwordless email system.
The application manages authentication states (Loading ⏳, LoggedIn ✅, LoggedOut ❌) using GetX and Obx.
Upon successful login, user authentication details (like private key) are persisted using shared_preferences.
Wallet Management 🔑:

Once logged in, users can view their Ethereum wallet address.
Provides the functionality to launch an external wallet service.
Allows users to sign messages or transactions, likely for blockchain interactions.
Displays user profile information, including a profile image 👤, fetched after login.
User Interface ✨:

A clean and modern UI with a dark theme.
Eye-catching gradient shaders on the application title ("Nexus") and the "Sign In With" text.
Clear input fields for email and well-styled buttons for login actions.
Dedicated sections for social login options.
A dedicated wallet screen displaying the user's address, profile, and options to launch the wallet or log out.
In essence, Nexus is a robust mobile gateway to Web3, simplifying user onboarding and wallet interaction through a secure and user-friendly Flutter interface.

## Features

|      | Component            | Details                                                                                                           |
| :--- | :------------------- | :-------------------------------------------------------------------------------------------------------------- |
| ⚙️  | **Architecture**     | <ul><li>Flutter-based mobile app with native integrations</li><li>Supports multi-platform (iOS & Android)</li><li>Uses CMake for native code (C++, CMakeLists.txt)</li><li>Gradle build scripts for Android</li></ul> |
| 🔩 | **Code Quality**     | <ul><li>Uses `analysis_options.yaml` for static analysis</li><li>Code organized into platform-specific directories</li><li>Consistent naming conventions</li></ul> |
| 📄 | **Documentation**    | <ul><li>Basic README structure</li><li>Includes dependencies and build instructions</li><li>Limited inline code comments observed</li></ul> |
| 🔌 | **Integrations**     | <ul><li>Flutter plugin system (`generated_plugin_registrant.cc`)</li><li>Native modules via CMake & Gradle</li><li>Uses `pub` for Dart package management</li></ul> |
| 🧩 | **Modularity**       | <ul><li>Separation of platform-specific code (iOS, Android, Linux)</li><li>Uses workspaces/settings for modular build</li><li>Plugins and native modules encapsulated</li></ul> |
| 🧪 | **Testing**          | <ul><li>Testing setup not explicitly detailed; likely uses `pubspec.yaml` for test dependencies</li><li>Potential unit tests in Dart and native code</li></ul> |
| ⚡️  | **Performance**      | <ul><li>Native code compiled with CMake for performance-critical parts</li><li>Flutter rendering optimized via standard practices</li></ul> |
| 🛡️ | **Security**         | <ul><li>Uses entitlements files (`debugprofile.entitlements`, `release.entitlements`) for iOS security</li><li>AndroidManifest.xml configured for permissions</li></ul> |
| 📦 | **Dependencies**     | <ul><li>Flutter dependencies managed via `pubspec.yaml` and `pubspec.lock`</li><li>Native dependencies via CMake and Gradle</li></ul> |

---

## Project Structure

```sh
└── Nexux-mobile-for-ETH-Global-2024/
    ├── README.md
    ├── analysis_options.yaml
    ├── android
    │   ├── .gitignore
    │   ├── app
    │   ├── build.gradle.kts
    │   ├── gradle
    │   ├── gradle.properties
    │   └── settings.gradle.kts
    ├── assets
    │   └── images
    ├── ios
    │   ├── .gitignore
    │   ├── Flutter
    │   ├── Runner
    │   ├── Runner.xcodeproj
    │   ├── Runner.xcworkspace
    │   └── RunnerTests
    ├── lib
    │   ├── controller.dart
    │   ├── login_screen.dart
    │   ├── main.dart
    │   ├── market_data_screen.dart
    │   ├── navigator_screen.dart
    │   ├── swap_screen.dart
    │   └── wallet_screen.dart
    ├── linux
    │   ├── .gitignore
    │   ├── CMakeLists.txt
    │   ├── flutter
    │   └── runner
    ├── macos
    │   ├── .gitignore
    │   ├── Flutter
    │   ├── Runner
    │   ├── Runner.xcodeproj
    │   ├── Runner.xcworkspace
    │   └── RunnerTests
    ├── pubspec.lock
    ├── pubspec.yaml
    ├── test
    │   └── widget_test.dart
    ├── web
    │   ├── favicon.png
    │   ├── icons
    │   ├── index.html
    │   └── manifest.json
    └── windows
        ├── .gitignore
        ├── CMakeLists.txt
        ├── flutter
        └── runner
```

---

### Project Index

<details open>
	<summary><b><code>NEXUX-MOBILE-FOR-ETH-GLOBAL-2024/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/pubspec.yaml'>pubspec.yaml</a></b></td>
					<td style='padding: 8px;'>- Defines the core configuration for the Flutter-based Nexus Mobile application, establishing project metadata, dependencies, assets, and environment settings<br>- It orchestrates the integration of essential packages for web3 authentication, local storage, HTTP communication, and UI navigation, enabling seamless development and deployment of a mobile app focused on decentralized web interactions and user experience.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/analysis_options.yaml'>analysis_options.yaml</a></b></td>
					<td style='padding: 8px;'>Defines static analysis rules and linting configurations to enforce code quality and best practices across the Dart and Flutter codebase, ensuring maintainability and consistency throughout the project.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/README.md'>README.md</a></b></td>
					<td style='padding: 8px;'>- Provides the foundational structure for the Nexus mobile application, enabling seamless user authentication, wallet management, and blockchain interactions within a Flutter environment<br>- It orchestrates core functionalities such as social and email login, private key handling, and Ethereum transaction signing, serving as the central component that integrates user onboarding, security, and blockchain connectivity to deliver a secure and user-friendly Web3 gateway.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- test Submodule -->
	<details>
		<summary><b>test</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ test</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/test/widget_test.dart'>widget_test.dart</a></b></td>
					<td style='padding: 8px;'>- Provides a fundamental widget test verifying core app functionality by simulating user interactions and ensuring the counter updates correctly<br>- It supports the overall testing strategy within the Flutter project, ensuring UI components behave as expected and maintaining application stability during development<br>- This test acts as a safeguard against regressions in the user interface logic.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- ios Submodule -->
	<details>
		<summary><b>ios</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ ios</b></code>
			<!-- Runner.xcodeproj Submodule -->
			<details>
				<summary><b>Runner.xcodeproj</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ ios.Runner.xcodeproj</b></code>
					<!-- project.xcworkspace Submodule -->
					<details>
						<summary><b>project.xcworkspace</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ ios.Runner.xcodeproj.project.xcworkspace</b></code>
							<!-- xcshareddata Submodule -->
							<details>
								<summary><b>xcshareddata</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ ios.Runner.xcodeproj.project.xcworkspace.xcshareddata</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/ios/Runner.xcodeproj/project.xcworkspace/xcshareddata/WorkspaceSettings.xcsettings'>WorkspaceSettings.xcsettings</a></b></td>
											<td style='padding: 8px;'>- Configures workspace settings to disable preview features within the iOS project environment, ensuring a streamlined development experience<br>- It aligns the workspace with project preferences, contributing to consistent behavior across team members and maintaining focus on core development tasks without unnecessary visual distractions<br>- This setup supports efficient collaboration and project management within the iOS codebase.</td>
										</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<!-- Runner.xcworkspace Submodule -->
			<details>
				<summary><b>Runner.xcworkspace</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ ios.Runner.xcworkspace</b></code>
					<!-- xcshareddata Submodule -->
					<details>
						<summary><b>xcshareddata</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ ios.Runner.xcworkspace.xcshareddata</b></code>
							<table style='width: 100%; border-collapse: collapse;'>
							<thead>
								<tr style='background-color: #f8f9fa;'>
									<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
									<th style='text-align: left; padding: 8px;'>Summary</th>
								</tr>
							</thead>
								<tr style='border-bottom: 1px solid #eee;'>
									<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/ios/Runner.xcworkspace/xcshareddata/WorkspaceSettings.xcsettings'>WorkspaceSettings.xcsettings</a></b></td>
									<td style='padding: 8px;'>- Configures workspace settings to disable live previews within the iOS development environment, ensuring a streamlined and distraction-free development process<br>- This setting helps maintain focus during code editing and testing by preventing automatic preview updates, thereby supporting efficient workflow management within the overall project architecture.</td>
								</tr>
							</table>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<!-- Runner Submodule -->
			<details>
				<summary><b>Runner</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ ios.Runner</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/ios/Runner/AppDelegate.swift'>AppDelegate.swift</a></b></td>
							<td style='padding: 8px;'>- Facilitates integration of Flutter with iOS by initializing the app and registering necessary plugins during launch<br>- Ensures seamless startup of the Flutter-based application within the iOS environment, serving as the primary entry point for app lifecycle management and plugin setup in the overall architecture.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/ios/Runner/Runner-Bridging-Header.h'>Runner-Bridging-Header.h</a></b></td>
							<td style='padding: 8px;'>- Facilitates integration between Flutter and native iOS components by bridging generated plugin registrations<br>- Ensures seamless communication and plugin functionality within the iOS environment, supporting the overall architecture of the Flutter application<br>- Acts as a crucial link in maintaining consistent plugin initialization and interaction across the iOS platform.</td>
						</tr>
					</table>
					<!-- Assets.xcassets Submodule -->
					<details>
						<summary><b>Assets.xcassets</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ ios.Runner.Assets.xcassets</b></code>
							<!-- AppIcon.appiconset Submodule -->
							<details>
								<summary><b>AppIcon.appiconset</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ ios.Runner.Assets.xcassets.AppIcon.appiconset</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/ios/Runner/Assets.xcassets/AppIcon.appiconset/Contents.json'>Contents.json</a></b></td>
											<td style='padding: 8px;'>- Defines the app icon assets for the iOS platform, specifying various image sizes and resolutions to ensure consistent branding across different devices and screen densities<br>- Serves as a central configuration for app icon presentation within the overall project architecture, supporting seamless visual identity and user recognition across iPhone, iPad, and marketing contexts.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- LaunchImage.imageset Submodule -->
							<details>
								<summary><b>LaunchImage.imageset</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ ios.Runner.Assets.xcassets.LaunchImage.imageset</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/ios/Runner/Assets.xcassets/LaunchImage.imageset/Contents.json'>Contents.json</a></b></td>
											<td style='padding: 8px;'>- Defines the launch screen assets for the iOS application, ensuring a consistent and visually appealing startup experience across all device sizes and resolutions<br>- Integrates multiple image scales to optimize display quality, contributing to the overall user interface architecture by providing a seamless initial impression during app launch.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/ios/Runner/Assets.xcassets/LaunchImage.imageset/README.md'>README.md</a></b></td>
											<td style='padding: 8px;'>- Defines customizable launch screen assets for the iOS application, enabling visual branding and user experience personalization during app startup<br>- Facilitates easy replacement of launch images through Xcode or direct asset management, ensuring the launch screen aligns with branding requirements and enhances initial user engagement within the overall app architecture.</td>
										</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<!-- RunnerTests Submodule -->
			<details>
				<summary><b>RunnerTests</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ ios.RunnerTests</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/ios/RunnerTests/RunnerTests.swift'>RunnerTests.swift</a></b></td>
							<td style='padding: 8px;'>- Provides a foundational test structure for the iOS Runner application within the Flutter project, enabling validation of core functionalities and ensuring stability during development<br>- Serves as a starting point for implementing unit tests to verify app behavior, contributing to overall code quality and reliability in the iOS platform integration.</td>
						</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<!-- lib Submodule -->
	<details>
		<summary><b>lib</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ lib</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/lib/login_screen.dart'>login_screen.dart</a></b></td>
					<td style='padding: 8px;'>- Defines the user authentication interface for the application, enabling users to sign in via email or social providers such as Google, GitHub, and Discord<br>- Facilitates seamless login experiences within the apps architecture, integrating various authentication methods into the overall user onboarding and access flow.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/lib/navigator_screen.dart'>navigator_screen.dart</a></b></td>
					<td style='padding: 8px;'>- Market Data, Swap, and Wallet<br>- Integrates persistent tab management with smooth animations and adaptive behavior for a cohesive user experience<br>- Serves as the primary navigation hub within the app’s architecture, orchestrating access to key functionalities while maintaining consistent UI state across screens.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/lib/wallet_screen.dart'>wallet_screen.dart</a></b></td>
					<td style='padding: 8px;'>- Provides a user interface for managing a Web3 wallet within a Flutter application, enabling users to view their wallet address, profile image, and perform key actions such as launching wallet services and logging out<br>- Integrates Web3Auth for authentication and wallet interactions, supporting seamless blockchain account management as part of the apps broader decentralized identity and asset handling architecture.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/lib/controller.dart'>controller.dart</a></b></td>
					<td style='padding: 8px;'>- Manages application state related to user authentication status within the overall architecture<br>- Acts as a centralized controller to track and update the authentication state dynamically, facilitating reactive UI updates and seamless user experience across the app<br>- Integrates with the GetX package to enable efficient state management and real-time responsiveness throughout the project.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/lib/main.dart'>main.dart</a></b></td>
					<td style='padding: 8px;'>- Facilitates user authentication and session management within the app, integrating multiple login providers via Web3Auth<br>- Manages app lifecycle events, initializes blockchain network connections, and controls navigation flow based on authentication state<br>- Serves as the entry point for user onboarding, ensuring secure access to blockchain features and maintaining seamless user experience across different platforms.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/lib/market_data_screen.dart'>market_data_screen.dart</a></b></td>
					<td style='padding: 8px;'>- Provides a user interface for displaying comprehensive market data on cryptocurrencies and stocks through tabbed views<br>- Facilitates real-time insights into asset prices, market rankings, capitalization, and last update timestamps, enabling users to compare and analyze financial instruments efficiently within a cohesive, scrollable layout.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/lib/swap_screen.dart'>swap_screen.dart</a></b></td>
					<td style='padding: 8px;'>- Facilitates user interactions for swapping cryptocurrencies, converting USD, and purchasing stocks within a financial app<br>- Provides a dynamic interface to select transaction types, input amounts, and execute trades, integrating core functionalities for managing digital assets and traditional investments seamlessly<br>- Serves as a central component for enabling diverse asset exchanges in the overall architecture.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- web Submodule -->
	<details>
		<summary><b>web</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ web</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/web/manifest.json'>manifest.json</a></b></td>
					<td style='padding: 8px;'>- Defines the web applications metadata and visual identity for the mobile experience, enabling a seamless and consistent user interface across devices<br>- It specifies app appearance, icons, and launch behavior, supporting the overall architecture by ensuring the Flutter-based mobile app delivers a polished, platform-optimized user experience aligned with the projects branding and functionality goals.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/web/index.html'>index.html</a></b></td>
					<td style='padding: 8px;'>- Defines the entry point for a Flutter web application, establishing the foundational HTML structure and metadata necessary for proper rendering, branding, and deployment<br>- It ensures the app loads correctly across different environments by configuring base paths, icons, and manifest links, serving as the gateway that integrates the Flutter app into the web platform within the overall project architecture.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- windows Submodule -->
	<details>
		<summary><b>windows</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ windows</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/CMakeLists.txt'>CMakeLists.txt</a></b></td>
					<td style='padding: 8px;'>- Defines the build configuration and installation process for the Windows version of the Nexus Mobile application, integrating Flutter components, managing plugin builds, and ensuring proper asset and library deployment<br>- Facilitates a streamlined, multi-configurable build environment to support development, profiling, and release modes, ensuring the application and its dependencies are correctly assembled and ready for deployment.</td>
				</tr>
			</table>
			<!-- runner Submodule -->
			<details>
				<summary><b>runner</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ windows.runner</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/Runner.rc'>Runner.rc</a></b></td>
							<td style='padding: 8px;'>Defines application metadata and resources for the Windows build of the project, including icons, version information, and localization details, ensuring consistent branding and identification across Windows environments within the overall architecture.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/flutter_window.cpp'>flutter_window.cpp</a></b></td>
							<td style='padding: 8px;'>- Facilitates the creation and management of a native Windows window integrated with Flutter, enabling seamless rendering of Flutter content within a Windows environment<br>- Handles window lifecycle events, manages the Flutter engine and view, and processes window messages to ensure proper display and plugin functionality, thereby serving as the bridge between Windows OS and Flutters rendering framework within the architecture.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/flutter_window.h'>flutter_window.h</a></b></td>
							<td style='padding: 8px;'>- Defines a Flutter window within a Windows environment, serving as a container that hosts and manages a Flutter view<br>- It facilitates integration of Flutter content into native Windows applications by creating, displaying, and handling the lifecycle of the embedded Flutter UI, ensuring seamless interaction between native Windows components and Flutter-based interfaces.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/CMakeLists.txt'>CMakeLists.txt</a></b></td>
							<td style='padding: 8px;'>- Defines the build configuration for the Windows runner executable, orchestrating compilation, linking, and integration of Flutter components<br>- It ensures the application is correctly assembled with necessary dependencies, versioning, and platform-specific settings, facilitating seamless deployment and execution within the overall Flutter-based architecture on Windows.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/win32_window.h'>win32_window.h</a></b></td>
							<td style='padding: 8px;'>- Defines a high DPI-aware Win32 window abstraction facilitating creation, display, and management of native Windows GUI windows<br>- Supports custom rendering and input handling through inheritance, enabling seamless integration of window behaviors within the applications architecture<br>- Serves as a foundational component for managing window lifecycle, message processing, and content embedding in the overall system.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/main.cpp'>main.cpp</a></b></td>
							<td style='padding: 8px;'>- Initialize and launch the Windows desktop application by setting up the main event loop, creating the application window, and integrating Flutters Dart runtime<br>- It serves as the entry point for rendering the Flutter UI within a native Windows environment, facilitating communication between the native system and Flutter components to deliver a seamless cross-platform experience.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/resource.h'>resource.h</a></b></td>
							<td style='padding: 8px;'>- Defines resource identifiers for the Windows runner application, including the application icon and default values for new resources<br>- Supports the overall architecture by enabling consistent resource management and integration within the Windows environment, ensuring the runners visual and functional elements are properly registered and accessible during execution.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/utils.cpp'>utils.cpp</a></b></td>
							<td style='padding: 8px;'>- Facilitates Windows-specific utility functions for the application, including console creation and command-line argument processing<br>- Ensures seamless integration between Windows environment and Flutter engine by managing output streams and converting command-line inputs from UTF-16 to UTF-8<br>- Supports robust startup and debugging capabilities within the Windows platform, contributing to the overall architectures stability and usability.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/runner.exe.manifest'>runner.exe.manifest</a></b></td>
							<td style='padding: 8px;'>- Defines the application manifest for the Windows runner executable, specifying DPI awareness and OS compatibility settings<br>- Ensures the runner operates correctly across Windows 10 and 11 by configuring display scaling behavior and supporting the appropriate operating system versions within the overall architecture.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/utils.h'>utils.h</a></b></td>
							<td style='padding: 8px;'>- Provides utility functions to facilitate Windows process management and command-line handling within the project<br>- It enables creating console windows with redirected output for debugging or interaction, converting UTF-16 encoded strings to UTF-8, and retrieving command-line arguments in a standardized format<br>- These utilities support seamless integration and communication between the Flutter library and the Windows environment.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/runner/win32_window.cpp'>win32_window.cpp</a></b></td>
							<td style='padding: 8px;'>- Implements a Win32 window management system tailored for Flutter on Windows, handling window creation, theming, DPI scaling, and message processing<br>- Facilitates seamless integration of native Windows UI elements with Flutter, ensuring proper window behavior, appearance, and responsiveness across different display settings and user preferences within the overall architecture.</td>
						</tr>
					</table>
				</blockquote>
			</details>
			<!-- flutter Submodule -->
			<details>
				<summary><b>flutter</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ windows.flutter</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/flutter/generated_plugin_registrant.h'>generated_plugin_registrant.h</a></b></td>
							<td style='padding: 8px;'>- Facilitates the registration of Flutter plugins within the Windows platform, ensuring seamless integration of native functionalities into the Flutter application<br>- Serves as a crucial component in the plugin initialization process, enabling the app to recognize and utilize platform-specific features efficiently<br>- Supports the overall architecture by maintaining a structured approach to plugin management during app startup.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/flutter/CMakeLists.txt'>CMakeLists.txt</a></b></td>
							<td style='padding: 8px;'>- Defines the build process for integrating Flutters Windows platform into the project architecture<br>- It manages the compilation and linking of Flutters core libraries, platform-specific wrappers, and plugin support, ensuring seamless communication between Flutter and native Windows components<br>- This setup facilitates the deployment of Flutter-based Windows applications within the overall codebase.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/flutter/generated_plugins.cmake'>generated_plugins.cmake</a></b></td>
							<td style='padding: 8px;'>- Facilitates integration of Flutter plugins into the Windows build system by dynamically including plugin directories and linking their libraries<br>- Ensures that all necessary plugin components are correctly incorporated into the application, supporting seamless plugin functionality within the overall architecture<br>- This setup streamlines plugin management and maintains consistency across the Windows platform.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/windows/flutter/generated_plugin_registrant.cc'>generated_plugin_registrant.cc</a></b></td>
							<td style='padding: 8px;'>- Registers platform-specific plugins for the Windows Flutter application, ensuring proper integration of external functionalities<br>- As part of the generated plugin registration system, it facilitates seamless plugin initialization during app startup, contributing to the overall modular architecture and extensibility of the Flutter project across different platforms.</td>
						</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<!-- macos Submodule -->
	<details>
		<summary><b>macos</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ macos</b></code>
			<!-- Flutter Submodule -->
			<details>
				<summary><b>Flutter</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ macos.Flutter</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/macos/Flutter/GeneratedPluginRegistrant.swift'>GeneratedPluginRegistrant.swift</a></b></td>
							<td style='padding: 8px;'>- Registers platform-specific plugins for the macOS Flutter application, enabling seamless integration of shared preferences functionality within the app<br>- It ensures that the SharedPreferences plugin is properly initialized and available for use across the macOS environment, supporting consistent data storage and retrieval in the overall project architecture.</td>
						</tr>
					</table>
				</blockquote>
			</details>
			<!-- Runner Submodule -->
			<details>
				<summary><b>Runner</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ macos.Runner</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/macos/Runner/AppDelegate.swift'>AppDelegate.swift</a></b></td>
							<td style='padding: 8px;'>- Defines the applications lifecycle behavior for the macOS platform within a Flutter-based architecture<br>- Manages window closure and state restoration, ensuring the app terminates when all windows are closed and supports secure state preservation, thereby integrating native macOS functionalities with Flutter to deliver a seamless user experience.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/macos/Runner/DebugProfile.entitlements'>DebugProfile.entitlements</a></b></td>
							<td style='padding: 8px;'>- Defines security entitlements for the macOS application, enabling sandboxing, allowing runtime code execution, and permitting network server operations<br>- These settings ensure the app operates within specified security boundaries while supporting necessary functionalities, aligning with the overall architecture that emphasizes secure, sandboxed execution for a robust and compliant macOS experience.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/macos/Runner/Release.entitlements'>Release.entitlements</a></b></td>
							<td style='padding: 8px;'>- Defines security entitlements for the macOS application, specifically enabling sandboxing to restrict app permissions<br>- This configuration enhances security by isolating the apps runtime environment, ensuring it operates within controlled boundaries<br>- It plays a crucial role in maintaining the overall architectures security posture and compliance with macOS app distribution standards.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/macos/Runner/MainFlutterWindow.swift'>MainFlutterWindow.swift</a></b></td>
							<td style='padding: 8px;'>- Defines the main application window for the macOS version, integrating Flutter content within a native Cocoa window<br>- It establishes the Flutter view controller as the primary interface, ensuring seamless rendering of Flutter UI components within the macOS environment and registering necessary plugins for full functionality within the app architecture.</td>
						</tr>
					</table>
					<!-- Assets.xcassets Submodule -->
					<details>
						<summary><b>Assets.xcassets</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ macos.Runner.Assets.xcassets</b></code>
							<!-- AppIcon.appiconset Submodule -->
							<details>
								<summary><b>AppIcon.appiconset</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ macos.Runner.Assets.xcassets.AppIcon.appiconset</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/macos/Runner/Assets.xcassets/AppIcon.appiconset/Contents.json'>Contents.json</a></b></td>
											<td style='padding: 8px;'>- Defines the set of application icons for the macOS version, specifying various sizes and resolutions to ensure consistent visual branding across different display contexts<br>- Integrates seamlessly into the overall app architecture by providing necessary assets for a polished user interface and maintaining visual consistency within the macOS ecosystem.</td>
										</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<!-- RunnerTests Submodule -->
			<details>
				<summary><b>RunnerTests</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ macos.RunnerTests</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/macos/RunnerTests/RunnerTests.swift'>RunnerTests.swift</a></b></td>
							<td style='padding: 8px;'>- Provides a foundational test structure for the macOS Flutter application, enabling validation of core functionalities within the Runner environment<br>- Serves as a starting point for implementing unit tests to ensure stability and correctness of the app’s integration with macOS-specific components, supporting overall project quality and reliability.</td>
						</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<!-- linux Submodule -->
	<details>
		<summary><b>linux</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ linux</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/linux/CMakeLists.txt'>CMakeLists.txt</a></b></td>
					<td style='padding: 8px;'>- Defines the build configuration and assembly process for the Linux version of the Nexus Mobile application, integrating Flutter components, system dependencies, and native assets<br>- Ensures proper compilation, bundling, and installation of the executable, libraries, and assets, facilitating a consistent and relocatable deployment aligned with the overall project architecture.</td>
				</tr>
			</table>
			<!-- runner Submodule -->
			<details>
				<summary><b>runner</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ linux.runner</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/linux/runner/CMakeLists.txt'>CMakeLists.txt</a></b></td>
							<td style='padding: 8px;'>- Defines the build configuration for the Linux runner application, specifying source files, dependencies, and build settings<br>- It orchestrates the compilation process, ensuring the application integrates Flutter and GTK components, and adheres to project-wide standards, thereby enabling a consistent and efficient build environment within the overall architecture.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/linux/runner/main.cc'>main.cc</a></b></td>
							<td style='padding: 8px;'>- Initialize and launch the application within the Linux environment, serving as the entry point for executing the software<br>- It sets up the application instance and manages its lifecycle, ensuring proper startup and integration with the systems application framework<br>- This core component facilitates the seamless execution of the entire codebase by orchestrating the applications initialization process.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/linux/runner/my_application.h'>my_application.h</a></b></td>
							<td style='padding: 8px;'>- Defines the interface for creating a Flutter-based application within the Linux environment, integrating GTK for native window management<br>- Serves as a foundational component that facilitates initializing and managing the applications lifecycle, ensuring seamless interaction between Flutter and Linux system resources within the overall architecture.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/linux/runner/my_application.cc'>my_application.cc</a></b></td>
							<td style='padding: 8px;'>- Defines the main application structure and lifecycle for a Linux-based Flutter desktop app, managing window creation, platform-specific UI adjustments, and plugin registration<br>- Facilitates seamless startup, activation, and shutdown processes, ensuring proper integration with desktop environments and handling command-line arguments for a cohesive user experience within the overall architecture.</td>
						</tr>
					</table>
				</blockquote>
			</details>
			<!-- flutter Submodule -->
			<details>
				<summary><b>flutter</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ linux.flutter</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/linux/flutter/generated_plugin_registrant.h'>generated_plugin_registrant.h</a></b></td>
							<td style='padding: 8px;'>- Facilitates the registration of Flutter plugins within the Linux platform, ensuring seamless integration of native functionalities into the Flutter application<br>- Serves as a crucial component in the plugin management architecture, enabling dynamic plugin initialization during app startup to support extended features and platform-specific capabilities.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/linux/flutter/CMakeLists.txt'>CMakeLists.txt</a></b></td>
							<td style='padding: 8px;'>- Defines the build process for integrating Flutters Linux library into the project, managing dependencies, configurations, and compilation steps<br>- Ensures that Flutters core components and platform-specific assets are correctly assembled and linked, facilitating seamless embedding of Flutter UI within the Linux environment as part of the overall architecture.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/linux/flutter/generated_plugins.cmake'>generated_plugins.cmake</a></b></td>
							<td style='padding: 8px;'>- Facilitates integration of Flutter plugins into the Linux build system by dynamically including plugin directories and linking their libraries<br>- Ensures seamless incorporation of both standard and FFI plugins, supporting modular extension of the application’s functionality within the overall architecture<br>- This setup enables efficient plugin management and dependency resolution during the build process.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/linux/flutter/generated_plugin_registrant.cc'>generated_plugin_registrant.cc</a></b></td>
							<td style='padding: 8px;'>- Registers Flutter plugins with the applications plugin registry during startup, ensuring seamless integration of native platform functionalities<br>- As part of the generated code, it facilitates plugin initialization without manual intervention, supporting the overall architecture by enabling smooth communication between Flutter and native code across the project.</td>
						</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<!-- android Submodule -->
	<details>
		<summary><b>android</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ android</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/android/settings.gradle.kts'>settings.gradle.kts</a></b></td>
					<td style='padding: 8px;'>- Defines plugin management and repository configurations for the Android build system within a Flutter project<br>- It ensures proper integration of Flutter SDK and plugins, facilitating consistent dependency resolution and plugin loading across the project architecture<br>- This setup is essential for maintaining a cohesive build environment aligned with Flutter and Android development standards.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/android/build.gradle.kts'>build.gradle.kts</a></b></td>
					<td style='padding: 8px;'>- Defines repository sources and configures build directories for all subprojects within the Android project, ensuring consistent dependency resolution and build environment setup<br>- Establishes a centralized build structure, facilitating efficient project management and streamlined build processes across the entire codebase.</td>
				</tr>
			</table>
			<!-- app Submodule -->
			<details>
				<summary><b>app</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ android.app</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/android/app/build.gradle.kts'>build.gradle.kts</a></b></td>
							<td style='padding: 8px;'>- Defines the Android build configuration for the mobile application, integrating Flutter with native Android development<br>- It specifies SDK versions, application identifiers, and build settings, ensuring seamless compilation and deployment of the app across different environments within the overall project architecture<br>- This setup facilitates the integration of Flutter modules into the native Android project.</td>
						</tr>
					</table>
					<!-- src Submodule -->
					<details>
						<summary><b>src</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ android.app.src</b></code>
							<!-- profile Submodule -->
							<details>
								<summary><b>profile</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ android.app.src.profile</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/android/app/src/profile/AndroidManifest.xml'>AndroidManifest.xml</a></b></td>
											<td style='padding: 8px;'>- Defines the necessary internet permission for development and debugging purposes within the Android profile build of the application<br>- It ensures the Flutter tool can communicate with the app during development, enabling features like hot reload and breakpoint setting, thereby supporting efficient testing and debugging workflows in the overall project architecture.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- main Submodule -->
							<details>
								<summary><b>main</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ android.app.src.main</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/android/app/src/main/AndroidManifest.xml'>AndroidManifest.xml</a></b></td>
											<td style='padding: 8px;'>- Defines the applications core Android configuration, including permissions, activity setup, intent filters, and theme settings, facilitating seamless integration of Flutter UI and handling external URI schemes<br>- Ensures proper app launch behavior, deep linking capabilities, and compatibility with Android system features within the overall project architecture.</td>
										</tr>
									</table>
									<!-- kotlin Submodule -->
									<details>
										<summary><b>kotlin</b></summary>
										<blockquote>
											<div class='directory-path' style='padding: 8px 0; color: #666;'>
												<code><b>⦿ android.app.src.main.kotlin</b></code>
											<!-- com Submodule -->
											<details>
												<summary><b>com</b></summary>
												<blockquote>
													<div class='directory-path' style='padding: 8px 0; color: #666;'>
														<code><b>⦿ android.app.src.main.kotlin.com</b></code>
													<!-- example Submodule -->
													<details>
														<summary><b>example</b></summary>
														<blockquote>
															<div class='directory-path' style='padding: 8px 0; color: #666;'>
																<code><b>⦿ android.app.src.main.kotlin.com.example</b></code>
															<!-- nexus_mobile Submodule -->
															<details>
																<summary><b>nexus_mobile</b></summary>
																<blockquote>
																	<div class='directory-path' style='padding: 8px 0; color: #666;'>
																		<code><b>⦿ android.app.src.main.kotlin.com.example.nexus_mobile</b></code>
																	<table style='width: 100%; border-collapse: collapse;'>
																	<thead>
																		<tr style='background-color: #f8f9fa;'>
																			<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
																			<th style='text-align: left; padding: 8px;'>Summary</th>
																		</tr>
																	</thead>
																		<tr style='border-bottom: 1px solid #eee;'>
																			<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/android/app/src/main/kotlin/com/example/nexus_mobile/MainActivity.kt'>MainActivity.kt</a></b></td>
																			<td style='padding: 8px;'>- Defines the main entry point for the Android application, integrating Flutters framework into the native Android environment<br>- It facilitates the launch and rendering of the Flutter UI within the Android app, serving as a bridge that connects the Flutter module to the Android platform, ensuring seamless user experience across both ecosystems.</td>
																		</tr>
																	</table>
																</blockquote>
															</details>
														</blockquote>
													</details>
												</blockquote>
											</details>
										</blockquote>
									</details>
								</blockquote>
							</details>
							<!-- debug Submodule -->
							<details>
								<summary><b>debug</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ android.app.src.debug</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024/blob/master/android/app/src/debug/AndroidManifest.xml'>AndroidManifest.xml</a></b></td>
											<td style='padding: 8px;'>- Defines necessary permissions for development activities within the Android environment, enabling communication between the Flutter tool and the application during debugging and hot reload sessions<br>- This setup ensures smooth development workflows by allowing network access essential for debugging features, contributing to the overall architectures focus on efficient, seamless app development and testing.</td>
										</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
				</blockquote>
			</details>
		</blockquote>
	</details>
</details>

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** Dart
- **Package Manager:** Pub, Cmake, Gradle

### Installation

Build Nexux-mobile-for-ETH-Global-2024 from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/LyNNxMooon/Nexux-mobile-for-ETH-Global-2024
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd Nexux-mobile-for-ETH-Global-2024
    ```

3. **Install the dependencies:**

**Using [pub](https://dart.dev/):**

```sh
❯ pub get
```
**Using [cmake](https://isocpp.org/):**

```sh
❯ cmake . && make
```
**Using [gradle](https://gradle.org/):**

```sh
❯ gradle build
```

### Usage

Run the project with:

**Using [pub](https://dart.dev/):**

```sh
dart {entrypoint}
```
**Using [cmake](https://isocpp.org/):**

```sh
./Nexux-mobile-for-ETH-Global-2024
```
**Using [gradle](https://gradle.org/):**

```sh
gradle run
```

### Testing

Nexux-mobile-for-eth-global-2024 uses the {__test_framework__} test framework. Run the test suite with:

**Using [pub](https://dart.dev/):**

```sh
pub run test
```
**Using [cmake](https://isocpp.org/):**

```sh
ctest
```
**Using [gradle](https://gradle.org/):**

```sh
gradle test
```

---

<div align="left"><a href="#top">⬆ Return</a></div>

---
