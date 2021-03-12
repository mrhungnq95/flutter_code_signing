CONTENTS OF THIS FILE
---------------------
 * Introduction
 * Requirements
 * Integrated Fastlane
 * Update Your iOS Project
 * Move Your Project To Github and Integrated Github Action
 * Make a Commit to Master Branch
 * Follow Github Action Process

INTRODUCTION
------------

The Easy way Code Signing used cloud Github Action.
Some Reasons Why You Need Code Signing:

    1. Continuous delivery your flutter apps help developer hours save deployment. 
    2. You don't need learn about Code Signing.
    3. You don't need have apple developer account.
    4. Secure and private your source code.

INTEGRATED FASTLANE
-------------

    1. Copy Gemfile and folder fastlane at my repo https://github.com/wem2017/flutter_code_signing
    2. Navigate to your ios folder and put file Gemfile and folder fastlane
    3. Change git_branch Matchfile to your application bundle id [com.huynh.example] if you use other application id please contact me

![alt text](https://github.com/wem2017/flutter_code_signing/blob/master/screenshot/fastlane.png?raw=true)

UPDATE XCODE PROJECT
-------------

    1. Verify & Update General info
    2. Verify & Update Signing & Capabilities
    3. Verify and Change value

![alt text](https://github.com/wem2017/flutter_code_signing/blob/master/screenshot/xcode1.png?raw=true)
![alt text](https://github.com/wem2017/flutter_code_signing/blob/master/screenshot/xcode2.png?raw=true)
![alt text](https://github.com/wem2017/flutter_code_signing/blob/master/screenshot/xcode3.png?raw=true)

SETUP REPO AND SECRETS
------------

Create repo recommend [private] and Setting your repo github with Secrets:

- PROVISIONING_PROFILE_SPECIFIER match AppStore passionui.maziflux
- DEVELOPER_APP_IDENTIFIER passionui.maziflux
- KEYCHAIN_NAME key
- KEYCHAIN_PASSWORD cuoilen@123
- MATCH_PASSWORD cuoilen@123
- GIT_AUTHORIZATION 1459a92a566c1df9593daddd302395bf3ee7821e
- FASTLANE_APPLE_ID huynh.developer@icloud.com
- FASTLANE_APPLE_APPLICATION_SPECIFIC_PASSWORD hwuw-ykoh-sxcb-xxlc
- DEVELOPER_PORTAL_TEAM_ID 3C2ZJ87Z72
- DEVELOPER_APP_ID 1501601754
- APP_STORE_CONNECT_TEAM_ID 120299252

If you can't access https://github.com/wem2017/apple_signing.git to clone certificate to Cloud Github Action and upload to my Appstore Connect<br/>
You can contact with me via wem2017.github.io for get GIT_AUTHORIZATION

PUSH CODE TO GITHUB AND INTEGRATED GITHUB ACTION
-------------
    
    1. Copy github workflow folder .github at my repo https://github.com/wem2017/flutter_code_signing to your source 
    2. Commit and push to master and check github action process

![alt text](https://github.com/wem2017/flutter_code_signing/blob/master/screenshot/github1.png?raw=true)
![alt text](https://github.com/wem2017/flutter_code_signing/blob/master/screenshot/github2.png?raw=true)
![alt text](https://github.com/wem2017/flutter_code_signing/blob/master/screenshot/github3.png?raw=true)
![alt text](https://github.com/wem2017/flutter_code_signing/blob/master/screenshot/appstore.png?raw=true)
