---
title: Prompt design
#subtitle: Brand marketing in the era of AI
layout: page
show_sidebar: false
---

# Getting started with prompt design

One key feature of many Generative AI systems is their ability to take natural language input (the same kind of language you would use in everyday conversation), understand this, and create an output. The initial text you enter is the ‘prompt’ and understanding how to write these is important when using Generative AI.  

For instance, an area that has emerged quickly is the ability to generate an image based on a typed request. Here’s an example from the [Adobe Firefly text-to-image generation tool](https://firefly.adobe.com/generate/images): 

<img width="835" alt="firefly" src="https://github.com/CagedEther/Nustory/assets/142103717/05e3f45e-cfdc-48ed-9a54-f49bbe268ac1">

Similarly, some systems will generate text based on a prompt. Here is an example from [Anthropic’s Claude system](https://claude.ai/): 

<img width="687" alt="claude" src="https://github.com/CagedEther/Nustory/assets/142103717/408074a5-c183-42d3-b1cf-b9005ac1f7c8">


For the remainder of this article, we’ll focus on text-based content generation as this currently has more varied use cases in the business context, however you’ll find resources at the bottom of this article that deal with image-based Generative AI. It’s worth noting that these systems can also generate videos, computer code, and practically any form of data you can imagine.  

We will start with a very simple case and build from there. We’ll be using [Open AI’s ChatGPT](https://chat.openai.com/) for these examples. 

## Google search on steroids

One particular use of Generative AI is for getting to answers more efficiently than using search engines like Google. Need a recipe for fruit scones? Here’s an excerpt of a suggested recipe: 

<img width="721" alt="scones" src="https://github.com/CagedEther/Nustory/assets/142103717/6f0dc04f-3074-4f15-9884-09d3b6a460ba">

If you’re tempted and [want to see the full recipe, check it out!](https://github.com/CagedEther/Nustory/blob/45ca702b38dcf745e761fc7b381eb112e3a60247/ChatGPT%20Example%20Scones.pdf) 

Sure, you can find multiple recipes online via a search engine. Indeed, tools like ChatGPT are trained on a vast amount of internet data, just like Google (albeit up to a specific point in time). But one key difference with Generative AI is that in this case it is working like an aggregator: looking at all the recipes and all the comments and using this to construct a composite of the most popular recipes. 

This is useful, but as you can probably guess, isn’t radically different from what has been available for some time now through web search. We’ll now explore areas where these tools really stand out. 

## Adding context and formatting results

The real ‘generative’ element of these tools comes in their ability to create formatted and stylized content. For instance, if you want help writing an email to your team at the end of a quarter, here’s an example prompt: 

<img width="761" alt="email" src="https://github.com/CagedEther/Nustory/assets/142103717/e05725f2-a967-4397-8c9c-e12513c392fe">

[Check out the full email](https://github.com/CagedEther/Nustory/blob/4a2bb1893551a380bfdc1758939ea2808e9f5600/ChatGPT%20Example%20Email.pdf) to see the different sections and formatting. 

You may feel that the prose isn’t quite in your tone and so while these tools are very good for getting you started, you will generally get best results when you edit the generated text to reflect your own style. 

It’s also worth experimenting with tweaking the prompt and seeing what result you get. For instance, one popular technique used to generate images is to reference a specific artist or design period. You can use the same approach with writing styles. 

## Threaded conversations

Many of the text-based systems allow you to continue the conversation and will ‘remember’ the context based on what was asked earlier. This allows for easy refinement and investigating follow-on ideas that you think of as the chat develops. Here’s an example: 

<img width="742" alt="recycling" src="https://github.com/CagedEther/Nustory/assets/142103717/9c9c408b-c7cc-4286-871b-7271031b0bbb">

As you can see, we didn’t need to reframe the context for the follow-on question. The system realizes that this question is in the same context as the first and took this into account in generating its response. 

This kind of threaded conversations can also be useful for asking for the same content in different formats, such as text for a blog, email, website page, etc. Note that these conversations persist over time so you can go back and continue where you left off, whether that’s hours, days, or months ahead. 

## Tailoring the results to your own content

In the examples so far, we’ve been using information that is general or could be found on the internet. What if you want to use this form of prompting to generate information from your own documents? 

Many of these tools allow you to upload your own content in formats like a pdf that can then be interrogated or summarized in the same way as we’ve described above. [Check out this example on summarizing an interview transcript](https://nustory.org/AI_for_text_summarization.html). 

## Going further with prompt design

We’ve only just touched the surface on what’s possible with prompt design for Generative AI systems, but hopefully you start to see how you can control these tools. Note we’ve chosen the term ‘prompt design’ over ‘prompt engineering’ (even though both terms are largely synonymous) to emphasize the creative aspects of this new paradigm. No coding or software engineering in the traditional sense is needed to use these systems. 

As Generative AI has an increasingly important role [across many areas of marketing](https://www.notion.so/Nustory-Forbes-marketing-AI-2b4a7c80277146a4ba6ec3773e660ebf?pvs=21), getting a good handle on prompt design is fundamental to unlocking the business value of this technology. 

Here are some resources to explore prompt design further: 

**Short courses on prompt design**

[IBM Skillsbuild: Mastering the art of prompting](https://skills.yourlearning.ibm.com/activity/MDL-298) <br>
[LI Learning: Introduction to prompt engineering](https://www.linkedin.com/learning/introduction-to-prompt-engineering-for-generative-ai/)

**More resources and links**

[Prompts useful for different areas of marketing](https://www.notion.so/bdb372c366fe43aa9e83af8106854f12?pvs=21) <br>
[Master these 8 ChatGPT prompting techniques](https://www.forbes.com/sites/jodiecook/2023/07/24/master-these-8-chatgpt-prompting-techniques-to-unlock-its-full-potential/?sh=42438a56c5f9) <br>
[Ten need-to-know techniques for prompt design](https://www.notion.so/watsonx-sample-prompts-07f0cfee5f6f41d48241a479927435ac?pvs=21) <br>
[Using ChatGPT to construct a founder’s story](https://www.notion.so/Nustory-Forbes-marketing-AI-2b4a7c80277146a4ba6ec3773e660ebf?pvs=21) <br>
[Open AI documentation on prompt design](https://platform.openai.com/docs/guides/gpt-best-practices/six-strategies-for-getting-better-results?utm_source=hackernewsletter&utm_medium=email&utm_term=fav) <br>
[Midjourney documentation on prompt design](https://www.notion.so/watsonx-sample-prompts-07f0cfee5f6f41d48241a479927435ac?pvs=21)
