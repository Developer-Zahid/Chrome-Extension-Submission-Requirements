# Chrome Extension Submission Requirements

Here is the full details of Chrome Extension submission requirements on Chrome Web Store

## Store listing

### Product details
- Title from package
- Summary from package
- Description* | *(16,000 character) | (Focus on explaining what the item does and why users should install it)*
- Category*
- Language* | *(Specifying your item’s language will help users find it. If you support multiple languages, then you should internationalize your item. [Learn more](https://developer.chrome.com/webstore/i18n))*

### Graphic assets
- Store icon* *(128x128 pixels)*

##### Global assets
- Global promo video | *(Enter a YouTube video URL. Example: https://www.youtube.com/watch?v=1234567890A)*
- Screenshots* | *(Up to a maximum of 5. [1280x800 or 640x400] JPEG or 24-bit PNG (no alpha). At least one is required )*
- Small promo tile | *(440x280 Canvas. JPEG or 24-bit PNG (no alpha))*
- Marquee promo tile | *(1400x560 Canvas. JPEG or 24-bit PNG (no alpha))*

### Additional fields
- Official URL | *(If your item is associated with a website that you own, select that website from the list. You can register as the owner for a site using Google Search Console.)*
- Homepage URL
- Support URL | *(Providing the URLs for description and support pages can improve your users’ experience and help make this item’s ratings and comments more meaningful. [Learn more](https://developer.chrome.com/docs/webstore/cws-dashboard-listing#support-url))*
- Mature content | *(Examples of mature content include sexual and suggestive content, strong language, violence, or a focus on the consumption or sale of alcohol, tobacco, or drugs. [Learn more](https://developer.chrome.com/webstore/rating))*

### Additional metrics
- Google Analytics 4 (GA4) | *(Once opted in, all developers who have access to this item will be able to view additional metrics in Google Analytics. [Learn more](https://developer.chrome.com/docs/webstore/google-analytics/))*

### Item support
- Visibility | *(Turn your item support on or off on your store listing. [Learn more](https://developer.chrome.com/docs/webstore/support-users))*


## Privacy

### Single purpose
An extension must have a single purpose that is narrow and easy-to-understand. [Learn more](https://developer.chrome.com/webstore/program_policies#extensions)
- Single purpose description* | *(1,000 character)*

### Permission justification
A [permission](https://developer.chrome.com/extensions/declare_permissions) is either one of a list of known strings, such as "activeTab", or a [match pattern](https://developer.chrome.com/extensions/match_patterns) giving access to one or more hosts. Remove any permission that is not needed to fulfill the single purpose of your extension. Requesting an unnecessary permission will result in this version being rejected. Examples:
- scripting justification* | *(1,000 character)*
- Host permission justification* | *(1,000 character) | A host permission is any [match pattern](https://developer.chrome.com/extensions/match_patterns) specified in the "permissions" and "content_scripts" fields of the extension manifest | Due to the Host Permission, your extension may require an in-depth review which will delay publishing.*

#### Are you using remote code?
Remote code is any JS or Wasm that is not included in the extension's package. This includes references to external files in `script` tags, modules pointing to external files, and strings evaluated through `eval()`.
- If select YES, then need justification | *(1,000 character)*

### Data usage
The content of this form will be displayed publicly on the item detail page. By publishing your item, you are certifying that these disclosures reflect the most up-to-date content of your privacy policy.

#### What user data do you plan to collect from users now or in the future? (See [FAQ](https://developer.chrome.com/docs/webstore/user_data/) for more information)
- Personally identifiable information | *(For example: name, address, email address, age, or identification number)*
- Health information | *(For example: heart rate data, medical history, symptoms, diagnoses, or procedures)*
- Financial and payment information | *(For example: transactions, credit card numbers, credit ratings, financial statements, or payment history)*
- Authentication information | *(For example: passwords, credentials, security question, or personal identification number (PIN))*
- Personal communications | *(For example: emails, texts, or chat messages)*
- Location | *(For example: region, IP address, GPS coordinates, or information about things near the user’s device)*
- Web history | *(The list of web pages a user has visited, as well as associated data such as page title and time of visit)*
- User activity | *(For example: network monitoring, clicks, mouse position, scroll, or keystroke logging)*
- Website content | *(For example: text, images, sounds, videos, or hyperlinks)*

#### I certify that the following disclosures are true:
- I do not sell or transfer user data to third parties, outside of the [approved use cases](https://developer.chrome.com/docs/webstore/program_policies/#limited_use)
- I do not use or transfer user data for purposes that are unrelated to my item's single purpose
- I do not use or transfer user data to determine creditworthiness or for lending purposes
*You must certify all three disclosures to comply with our [Developer Program Policies](https://developer.chrome.com/webstore/program_policies)*

### Privacy policy
An extension must have a privacy policy if it collects user data. [Learn more](https://developer.chrome.com/docs/webstore/program-policies/privacy/)
- Privacy policy URL | *(2,048 character)*


## Distribution

### Payments
Select if your item will be free of charge or if it offers in-app purchases
- Free of charge | *Your item is free of charge and doesn't contain any functionality to purchase additional goods, content, services or functionality*
-   Contains in-app purchases | *(Your item contains functionality to purchase items, additional features or subscriptions. Selecting this option will display an "in-app purchases" badge on the item detail page)*

### Visibility
- Public | *(Everyone in selected countries can see it)*
- Unlisted | *(Only people with the link can see it (Note: Item may still appear in web search engine results).)*
-   Private | *(option disabled because item is published publicly. You must unpublish this item before it can be published to trusted testers. Users who already have this item installed will get updated to the new version if they are added to the trusted tester list. Alternatively, you can create a new item and publish it to trusted testers.)*

### Distribution
- All regions
- Or specific countries


## Test instructions
Help us review your extension's core functionality by providing test instructions if login, authentication, or specific setup is required. Enter any necessary test account credentials and steps below. The information provided in this form will be shared with the Chrome Web Store team.
Providing these details is essential for a complete evaluation. All information provided is confidential and used solely for review purposes.

### Credentials
- Username | *(100 character) | Username for testing the extension*
- Password | *(100 character) | If any, for the provided username*

### Additional instructions
Provide any instructions required to access core extension functionality if additional setup is required beyond entering the provided username and password | *(500 character)*
