# Walter the Alien Podcast
### An experiment in Human + AI creative collaboration

<i>Human Life from an Alien Perspective</i> is a YouTube podcast that explores Earth through the curious eyes of Walter — a Martian anthropologist. In each episode, Walter offers thoughtful, sometimes humorous insights into human behavior, culture, and daily life. With an outsider’s clarity and a researcher’s rigor, he unpacks everything from food and fashion to rituals, subcultures, and social norms. It’s a fresh, reflective look at what it means to be human — from someone who isn’t.

YouTube channel<br>
Human Life from an Alien Perspective<br>
https://www.youtube.com/@walterthealien

<hr>
<a href="https://www.youtube.com/@walterthealien">
  <img src="https://github.com/vbookshelf/Walter-the-Alien-Podcast/blob/main/images/channel.png" alt="Ep1 - Hello, Earth" width="1000">
</a>

Hello, Earth. My name is Walter. I’m an anthropologist from Mars. A quiet observer of your world for the past three years. I walk your streets, listen to your voices, and watch the rhythm of your lives — not to interfere, but to understand. This podcast is my space to reflect. To share out loud what I see and feel.

<hr>
<br>

## Project Overview

Generative AI is opening up new ways to create by separating imagination from technical skill.

Many people have strong creative instincts but haven’t had the chance to develop the skills (e.g. drawing or writing) to express their creativity. AI can help bridge that gap by making it easier to bring ideas to life without years of technical training.

Walter the Alien is a storytelling experiment in human+AI collaboration. I define the story arc. AI generates narrative components. I edit and shape those outputs into podcast scripts. Then I use "Google Generate Speech" to convert the scripts into podcast episodes. 

I only use free tools.

This project is a practical exploration of how AI can support the human creative process.

<br>
<br>

## Tools

- ChatGPT<br>
Used to generate story ideas and drafts.
- Google Generate Speech<br>
Used to convert the text to audio.<br>
https://aistudio.google.com/generate-speech
- Google NotebookLM Audio Overview<br>
  Used to generate a third party perspective on the content. I also use it to check that the podcast episodes complement each other without creating conflicts and inconsistencies in the overall narrative.<br>
https://notebooklm.google.com/
- iMovie<br>
Used to create the YouTube videos.

## Resources
- Book<br>
On Writing Well: The Classic Guide to Writing Nonfiction<br>
William Zinsser

- Book<br>
The Elements of Style<br>
 William Strunk Jr. and E. B. White

<br>

## Lessons Learned - Rough Notes as the project progresses

1- Model Version Anxiety: The style and tone of the generated text are heavily dependant on the model version. If you somehow lose access to your version of a model, say the model gets updated to a new version by the API provider, then the style of the prose you are generating can change dramatically. This can ruin a long term creative project. To reduce this risk it's better to use an open source model that you run locally or run using a cloud GPU rental service.

2- Literary text editing: ChatGPT is able to edit in accordance with the Chicago Manual of Style. Gemini is not able to do this. Also, ChatGPT understands that editing style needs to suit the context.

3- ChatGPT prompt I used for editing: 
```
I will give you some text. Please check the spelling. Please check that it follows creative prose and poetic formatting conventions. Please use American punctuation conventions and American spelling. It will be published as an ebook and as a paperback. Make sure the text is fully  aligned with American publishing conventions e.g. remove the spaces around em dashes. 
Please rewrite with your corrections included. Also, at the end, list all the changes you’ve made.
###
[... Paste text here...]
```
Because ChatGPT has a limited context memory, this prompt needs to be added to every every block of text you need to edit. As the conversation gets longer, ChatGPT's performance degrades.

4- Amazon KDP has a high level of trust in automated AI classification systems that, in reality, are not reliable. This confidence is evidenced by the fact that the system summarily BLOCKS when it detects issues - with a book title for example. There's no option to revise and resubmit. You are told to contact support but when clicking the 'Contact Us' button the user is greeted with a labyrinth of links to documentation. It's not clear how to send a message to the support team. Clearly the system is set up to reduce the number of support requests that are sent. I think that this trend of placing high levels of confidence in imperfect AI systems does not bode well for the future. When AI systems are used by governments, for example, these system errors could lead to social unrest because the general population will just not have any other recourse.

These days many people are buidling businesses on platforms like YouTube, Amazon and Etsy - as a source of primary income. When planning a venture that relies on this business model, I think that people need to keep this risk in mind: At any moment your entire livelihood could be wiped out if you get banned or blocked due to a system error. And with millions of users on these platforms, you have a slim chance of getting in touch with a real support human to help solve your problem.

