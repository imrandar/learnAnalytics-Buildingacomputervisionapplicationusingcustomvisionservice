# Welcome 

Welcome to this workshop on the custom vision service. In this workshop, we will focus on hands-on activities that develop proficiency with the custom vision service.

# Goals

Most challenges observed by customers in these realms are in stitching multiple services together. As such, where possible, we have tried to place key concepts in the context of a broader example. 

At the end of this workshop, you should be able to:

- Understand how to configure your apps to call Cognitive Services
- Build an application that calls various Cognitive Services APIs (specifically Computer Vision)
- Understand how to implement Azure Search features to provide a positive search experience inside applications
- Configure an Azure Search service to extend your data to enable full-text, language-aware search
- Build, train, and publish a LUIS model to help your bot communicate effectively
- Build an intelligent bot using Microsoft Bot Framework that leverages LUIS and Azure Search
- Effectively log chat conversations in your bot
- Perform rapid development/testing with Ngrok and test your bots with unit tests and direct bot communication
- Effectively leverage the custom vision service to create image classification services that can then be leveraged by an application

# Pre-requisites

This workshop is meant for an AI Developer on Azure. Since this is only a short workshop, there are certain things you need before you arrive.

Firstly, you should have some previous exposure to Visual Studio. We will be using it for everything we are building in the workshop, so you should be familiar with [how to use it](https://docs.microsoft.com/en-us/visualstudio/ide/visual-studio-ide) to create applications. Additionally, this is not a class where we teach you how to code or develop applications. We assume you have some familiarity with C# (intermediate level - you can learn [here](https://mva.microsoft.com/en-us/training-courses/c-fundamentals-for-absolute-beginners-16169?l=Lvld4EQIC_2706218949)), but you do not know how to implement solutions with Cognitive Services. 

Secondly, you should have some experience developing bots with Microsoft's Bot Framework. We won't spend a lot of time discussing how to design them or how dialogs work. If you are not familiar with the Bot Framework, you should take [this Microsoft Virtual Academy course](https://mva.microsoft.com/en-us/training-courses/creating-bots-in-the-microsoft-bot-framework-using-c-17590#!) prior to attending the workshop.

Thirdly, you should have experience with the portal and be able to create resources (and spend money) on Azure. We will not be providing Azure passes for this workshop.

Finally, before arriving at the workshop, we expect you to have completed [1_Setup](./lab01.1-computer_vision/1_Setup.md) along with the configuring the following for Custom Vision:
  * Training API Key: The training API key allows you to create, manage and train Custom Vision project programmatically.
    * You can obtain a key by creating a new project at https://customvision.ai and then clicking on the “setting” gear in the top right. 
 


# Agenda

Please note: This is a rough agenda, and the schedule is subject to change pending class activities and interaction.

- Day 1: Cognitive Services
  - 8-9 (optional): Setup assistance
  - 9-10: Introduction and Context for Cognitive Services
  - 10-12: [Lab 1.1: Simplifying Cognitive Services App Development using Portable Class Libraries][lab-cogsrvc-301]
  - 12-1: Lunch
  - 1-1:30: [Lab 1.2: Creating an Image Classification Application using the Custom Vision Service I][lab-cogsrvc-321]
  - 1:30-2:00: [Lab 1.3: Creating an Image Classification Application using the Custom Vision Service II][lab-cogsrvc-322]
  - 2:00-2:30: [Lab 1.4: Creating an Image Classification Application using the Custom Vision Service III][lab-cogsrvc-323]
  - 2:30-3:45: [Lab 1.5: Developing Intelligent Applications with LUIS][lab-cogsrvc-341]
  - 3:45-5: [Business Case I - Cognitive Services](./lab01.6-bootcamp_case_1/case_part1.md)
- Day 2: Bots
  - 9-10: [Lab 2.1: Developing Intelligent Applications with Azure Search][lab-azsearch-301]
  - 10-10:30: Introduction and Context for Bots
  - 10:30-12: [Lab 2.2: Bulding Intelligent Bots][lab-intelbot-301]
  - 12-1: Lunch
  - 1-2:  [Lab 2.3: Log Chat Conversations in your Bot][lab-intelbot-311]
  - 2-3: [Lab 2.4: Testing your Bot][lab-intelbot-321]
  - 3-4: [Business Case II - Bots](./lab02.5-bootcamp_case_2/Case_Part2.md)
  - 4-5: Q&A and Feedback for Emerging AI Bootcamp


# Discussion Forum

We will also use a gitter forum for discussion. Please post comments and questions [here][gitter].

[lab-cogsrvc-301]: https://aka.ms/LearnAI-EmergingAIDevBootcamp-cogsrvc-301
[lab-cogsrvc-321]: https://aka.ms/LearnAI-EmergingAIDevBootcamp-cogsrvc-321
[lab-cogsrvc-322]: https://aka.ms/LearnAI-EmergingAIDevBootcamp-cogsrvc-322
[lab-cogsrvc-323]: https://aka.ms/LearnAI-EmergingAIDevBootcamp-cogsrvc-323
[lab-cogsrvc-341]: https://aka.ms/LearnAI-EmergingAIDevBootcamp-cogsrvc-341
[lab-azsearch-301]: https://aka.ms/LearnAI-EmergingAIDevBootcamp-azsearch-301
[lab-intelbot-301]: https://aka.ms/LearnAI-EmergingAIDevBootcamp-intelbot-301
[lab-intelbot-311]: https://aka.ms/LearnAI-EmergingAIDevBootcamp-intelbot-311
[lab-intelbot-321]:https://aka.ms/LearnAI-EmergingAIDevBootcamp-intelbot-321
[gitter]: https://gitter.im/LearnAI-Bootcamps


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
