In this unit, you'll analyze the criteria that experts employ when they choose an AI service for a specific business need.  Understanding the criteria can also help you better understand the nuanced differences among the products.

## Are you building a virtual agent that interfaces with humans via natural language?

Use Azure Bot Service when you need to create a virtual agent to interact with humans by using natural language. Bot Service integrates knowledge sources, natural language processing, and form factors to allow interaction across different channels.

Bot Service solutions usually rely on other AI services for such things as natural language understanding or even translation for localizing replies into a customer's preferred language.

Before you jump in to build a custom chat experience by using Bot Service, it might make sense to search for prebuilt, no-code solutions that cover common scenarios. For example, you can use QnA Maker, which is available from Azure Marketplace, to build, train, and publish a sophisticated bot that uses FAQ pages, support websites, product manuals, SharePoint documents, or editorial content through an easy-to-use UI or via REST APIs. 

Likewise, Power Virtual Agents integrates with Microsoft Power Platform so that you can use hundreds of prebuilt connectors for data input. You can extend Power Virtual Agents by building custom workflows with Power Automate, and if you feel that the out-of-the-box experience is too limiting, you can still build more complex interactions with Microsoft Bot Framework.

## Do you need a service that can understand the content and meaning of images, video, or audio, or that can translate text into a different language?

Use Azure Cognitive Services when it comes to general purpose tasks, such as performing speech to text, integrating with search, or identifying the objects in an image. Azure Cognitive Services is *general purpose*, meaning that many different kinds of customers can benefit from the work that Microsoft has already done to train and test these models and offer them inexpensively at scale.

## Do you need to predict user behavior or provide users with personalized recommendations in your app?

The Azure Cognitive Services Personalizer service watches your users' actions within an application. You can use Personalizer to predict their behavior and provide relevant experiences as it identifies usage patterns. Here again, you could capture and store user behavior and create your own custom Azure Machine Learning solution to do these things, but this approach would require much effort and expense.

## Will your app predict future outcomes based on private historical data?

Choose Azure Machine Learning when you need to analyze data to predict future outcomes. For example, suppose you need to analyze years' worth of financial transactions to discover new patterns that could help you create new products and services for your company's clients and then offer those new services during routine customer service calls. When you're working with proprietary data, you'll likely need to build a more custom-tailored machine learning model.

## Do you need to build a model by using your own data or perform a different task than those listed above?

Use Azure Machine Learning for maximum flexibility. Data scientists and AI engineers can use the tools they're familiar with and the data you provide to develop deep learning and machine learning models that are tuned for your particular requirements.