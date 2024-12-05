# Release Information

* **Version**: 3.1.0 ![Preview icon](./docs/res/icon-preview.svg)  
* **Certified**: Yes
* **Publisher**: Fortinet
* **Compatible Version**: 7.6.0 and later
* [Release Notes](./release_notes.md)

>[!NOTE]
>This is a preview version of **FortiAI** designed to demonstrate the potential of Generative AI in FortiSOAR. Preview releases are a beta release. This means that release is intended to get feedback and might not be best suited for production level deployments. Feature availability and support for preview releases will continue to improve as the solution/feature matures.

# Overview

FortiAI is a context-aware GenAI security assistant that transforms how security professionals operate and interact with threat alerts. It simplifies complex analysis and response tasks, enabling users to issue natural language commands for data analysis, threat identification, and remediation within FortiSOAR. With capabilities like generating playbooks, escalating alerts to incidents, setting up war rooms, and crafting [Jinja](https://jinja.palletsprojects.com/en/3.1.x/) expressions, FortiAI accelerates response cycles and enhances accuracy. It supports various functions, including blocking and enriching indicators, linking records, and creating comprehensive response plans, empowering security teams to address modern threats efficiently and effectively.

Its unique feature, among others, is its ability to generate playbook blocks tailored to scenarios defined by you, giving you a head start in automating and enhancing your use cases. Whether you are a seasoned playbook developer or just starting out, FortiAI is your go-to partner for streamlined and efficient playbook design.

## Filtering Feature Overview  

FortiAI now includes advanced filtering functionality, allowing users to refine their search for records based on specific criteria. This feature empowers users to quickly retrieve targeted data, such as alerts, incidents, or indicators, improving workflow efficiency. The benefits of this feature include:

- **Enhanced Precision**: Apply specific filters based on severity, status, or other criteria to retrieve exactly what you need.
- **Time-Saving**: Quickly narrow down search results, reducing the time spent sifting through data and improving decision-making.

## Voice Support Overview

FortiAI now includes voice-to-natural-language functionality, enabling hands-free interaction. This feature allows users to give voice commands for tasks such as generating playbooks, filtering records, or blocking indicators, streamlining workflows and increasing accessibility. This feature has multiple benefits like the following:

- **Enhanced Usability**: Issue commands without typing, ideal for multitasking.
- **Efficiency**: Quickly perform actions through voice, reducing operational time.

> [!Note]
> The *Voice Recognition* feature is currently unsupported on the Firefox browser as the webkit `SpeechRecognition` is not compatible with Mozilla Firefox. Hence, the mic button is not available when the FortiSOAR&trade; environment is accessed using the Firefox browser.

## Data Privacy Notice 

The FortiAI lets you connect your Fortinet account to your own OpenAI account, using your own OpenAI Assistant API key. This integration will send data from your Fortinet account to OpenAI and will show you responses from OpenAI. Fortinet does not verify or correct these responses and has no responsibility for them. OpenAI Assistant is operated by a third party, not Fortinet. You must exercise discretion and independently verify any information or recommendations you receive from OpenAI before relying on them.

Before using the FortiAI, we recommend that you review OpenAI’s API Platform privacy policy to understand how your data may be used and protected. By continuing to use FortiAI, you acknowledge and agree to the terms outlined in OpenAI’s privacy policy. 

For any further questions or concerns about your privacy, refer to [OpenAI’s privacy policy](https://openai.com/policies/privacy-policy). 

## Additional Resources 

- [Advanced Usage](./docs/advanced-usage.md)
- [Troubleshooting](./docs/troubleshooting.md)
- Try and be astonished!
    - [Prompts for filtering *alert* records](./docs/prompts-for-filtering-alert-records.md)
    - [Prompts for filtering *incident* records](./docs/prompts-for-filtering-incident-records.md)
    - [Prompts for filtering *indicator* records](./docs/prompts-for-filtering-indicator-records.md)

# Next Steps

| [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) |
| -------------------------------------------- | ---------------------------------------------- | ------------------------ | ------------------------------ |
