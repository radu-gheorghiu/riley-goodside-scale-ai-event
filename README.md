## Chat & Summary (later)

Scale Virtual Events
Home
/
Events
/
LLM Prompt Engineering and RLHF: History and Techniques
/
Live
timezone
+02:00 EET
Radu Gheorghiu
Live
Agenda
Match
People
Messages
Help
COMMUNITY
Note this talk was recorded before the public release of OpenAI’s new ChatGPT API — to learn more about how ChatGPT compares with GPT-3, check out our head-to-head comparison (https://scale.com/blog/chatgpt-vs-davinci) on Scale’s blog, and stay tuned for live Q&A following Riley’s talk!


Radu Gheorghiu
Data Engineer @ Independent Consultant
@Vishal, I tried this. But it halucinated quite a bit. Most of the links/articles it provided were actually fake, or at least I couldn't find them on Google / Bing.

Connor Hagen
Senior Business Development Manager @ Microsoft
@Javid did you try prompt flattering?

Charles Frye
Deep Learning Educator @ Full Stack Deep Learning
@Javid smaller models, like flan-ul2, will get that one right. If you use the formatting tricks presented here, the large models will as well.

Marc Cenedella
Founder @ Leet Resumes
@riley - thank you for your absurdly generous leadership in this space. I'm new to AI and have found it is the most welcoming, collaborative, smart, and big-hearted group of people I've ever come across, and you are at the top of that list!

Riley Goodside
Staff Prompt Engineer @ Scale
@Ana It's a rare case when the logprops of the top 2 tokens are very close — there's some computational optimization on the API. I know Boris Power (of OpenAI) gave some details about it on a Twitter thread, if you search for "deterministic" on his Twitter you'd probably find it.

Riley Goodside
Staff Prompt Engineer @ Scale
@Marc: Thank you!

Vishal Singhania
Director, Product Management @ Medallia Inc
@radu... wow fake links.. its generatring that too!

John Kohlmeyer
Developer @ DriveCentric
this is immediately before Bing chat threatened the user

Ana Ferreira
data ops @ talkdesk
thank you @riley, will do so

Amir Jamal Kaddoura
Digital Marketer/Prompt Engineer @ WSO
@Ana The behavior of a system at a temperature of zero can depend on various factors and it's difficult to determine the specific cause of the change in response without more information about the prompt and system in question.

Minsuk Kang
Software Engineer @ Scale
@riley, I might have missed the part, but do you also explain how ChatGPT persists context in a chat session? Is that done through prompt engineering?

Brandon E
Laserist @ VisionLight Events
@Javid - i just tried it and ChatGPT got it right..it stated that volume is different...

David Plon
Co-founder & CEO @ Portrait Analytics
@riley Thanks!

Riley Goodside
Staff Prompt Engineer @ Scale
@Minsuk: Essentially, yes — the process is made a bit more clear with the ChatGPT API release. There's an extension to the tokenization, but it's still technically compiled to a prompt.

Shaun VanWeelden
Field Engineering Manager @ Scale AI
Where can we hear Riley reciting more poetry?

Connor Hagen
Senior Business Development Manager @ Microsoft
we need a slow zoom-in here

Cristiano Giardina
President @ Pattern Logic
@Vishal it can't do that - but Bing Chat can, although not perfect. You can improve accuracy for a specific knowledge-base by embedding it and then performing a cosine similarity function to match your question to the correct context. In that case, you could also generate references to the relevant pages in the knowledge-base

Vishal Singhania
Director, Product Management @ Medallia Inc
Wow!

Vishal Singhania
Director, Product Management @ Medallia Inc
@Cristiano Thanks

Riley Goodside
Staff Prompt Engineer @ Scale
(I have this poem memorized btw — it's a useful party trick)

Ana Ferreira
data ops @ talkdesk
ahaha

Diego Asua
Data scientist @ BlakBear
To be ChatGPT or not to be

Vishal Singhania
Director, Product Management @ Medallia Inc
@riley haha

Britton Winterrose
Startup Solutions Architect - Y Combinator @ Amazon Web Services
Love it

John Kohlmeyer
Developer @ DriveCentric
@shaun just use elevenlabs

Cristiano Giardina
President @ Pattern Logic
Awesome

Jeff Choi
Business Director @ Coxwave
<3

David Bosnak
CEO @ Attune Media Labs
clap

Irina Poslavsky
Founder @ KoTrie
Thank you!

Marc Cenedella
Founder @ Leet Resumes
clap clap clap

Haseeb Mohammed
Principal Machine Learning Engineer @ Amgen
AWESOME

Fatma Tarlaci
VP of Engineering @ OpenTeams
@riley not only your parents, we are all very impressed I think :))

Connor Hagen
Senior Business Development Manager @ Microsoft
clapclapclap

Scott Ambler
Agile Data Coach @ Ambysoft Inc.
One of the most important uses of AI is to impress the parental units

Joe Kobrianos
Product and Tech @ Mersive
Thank you!

Brandon E
Laserist @ VisionLight Events
The only thing I can recite off by heart is Vanilla Ice, Ice Ice Baby! lol

Shaun VanWeelden
Field Engineering Manager @ Scale AI
Whoo Riley and Bihan!!

Cristiano Giardina
President @ Pattern Logic
@Riley Do you think it's possible to create jailbreak-proof LLMs without additional systems layered on top?
It seems that Anthropic's Claude is the most resilient to jailbreaking and as far as I understand is because they have a variety of systems working in concert to filter the output.
The other public-facing LLMs seem to have very simple filters on top (sometimes as simple as regex)…

Sam Ching
PM @ Duolingo
I wonder if anyone here (Riley or anyone else) has found a good way to track / measure differences in prompt output across different model versions (or providers) (chatgpt-api vs davinci-003 etc.), esp. since recent models have included prompt optimization techniques like CoT

Yi Ding
Programmer @ Red Oak Technologies
👏

Rebecca Woerner
Head of Events & Field Marketing @ Scale AI
@brandon we all have our strengths.

Charles Frye
Deep Learning Educator @ Full Stack Deep Learning
@Riley: it seems like soft prompts are not particularly popular, despite cool early results. Do you think that's because of API limitations or because of limitations to the technique?

Rebecca Woerner
Head of Events & Field Marketing @ Scale AI
Feel free to drop any questions here in the chat! And we'll funnel them to Bihan and Riley to answer

Radu Gheorghiu
Data Engineer @ Independent Consultant
ChatGPT asked me to ask you this question: "What inspired you to pursue a career as a prompt engineer at Scale AI, and what do you find to be the most rewarding aspect of your job?"

Nathan Baschez
Founder @ Lex
@sam check out
https://twitter.com/natfriedman/status/1633582489850773504

Connor Hagen
Senior Business Development Manager @ Microsoft
What are your thoughts on The Waluigi Effect? Do you think it will be a long-term concern for agentic tasks?

James Daniel
Applications Specialist II @ Wayne State University
@Riley What do you think about the anomalous tokens popularized by the SolidGoldMagikarp LessWrong post?

Sam Ching
PM @ Duolingo
Nathan - thanks! Was down ytd but will try again today!

Tim Nunamaker
Engineer @ Vana
@Riley will prompt engineering always be important as a fundamental skill, or are better models likely to mitigate the need for prompt engineering altogether?

Radu Gheorghiu
Data Engineer @ Independent Consultant
A few weeks ago I was able to get ChatGPT to only give me the response in JSON as I wanted, without the starting text. About 2-3 weeks ago, it feels like things changed and I can't get a reply without the friendly text at the beginning.

Joshua Batson
research scientist @ self
If you could fine tune or RLHF to improve GPT-K, what would you do to try to make prompting easier, or reveal more capabilities and make them easier to use?

Michael Lam
PM @ Speak
What do you think is the limiting factor that prevents GPT3 from doing math correctly? Seems like it understands logic, but not the rules of arithmetic.

Javid Lakha
Research Engineer @ Legatics
@Michael - byte pair encoding

Arjun Patel
Data Scientist @ Appen
Thanks so much for the seminar all!

Emily Quiles
Generalist @ None ATM
What are your tips to get a job in prompt engineering? I see there's a lot of talk about it, but very little jobs on the market. Is it also under another title?

Asia Butler
Front Desk Agent @ White Buffalo Club
Could prompt engineering be useful for the hospitality industry? I could see mu

Jorge H Cardona G
CMIO @ Analitica-MD
@Javid:I think that attention part of transformers has some incidence too

Asia Butler
Front Desk Agent @ White Buffalo Club
I could see multiple uses but lacking a software engineering degree leaves me confused.

Josh Pazmino
Developer @ Conscious Data
any thoughts on simulators / the waluigi effect?

Haseeb Mohammed
Principal Machine Learning Engineer @ Amgen
can someone feed this chat into chatgpt, and ask it to produce a summary of key points and questions please

Amir Jamal Kaddoura
Digital Marketer/Prompt Engineer @ WSO
@Asia of course... Automate, Automate, Automate.

Brandon E
Laserist @ VisionLight Events
For newbies to the 'prompt engineering' world, where would you recommend we go for real in-depth training (but easy-to-understand) and information on studying this fascinating new world of AI?

Touqir Sajed
AI Research Scientist @ LG Electronics Canada Inc
Awesome presentation Riley! Can you recommend us further resources on Prompt Engineering such as how industries are leveraging prompt engineering in new ways? Would be great to have a platform for industry experts to share tips and tricks on Prompt Engineering,

Javid Lakha
Research Engineer @ Legatics
@Jorge - how so? The windows are large and they have no problem writing code

Vishal Singhania
Director, Product Management @ Medallia Inc
How can Product Manager role help with optimizing prompt engineering?

Carlos Salas
Senior Data Scientist @ Salesloft
@Brandon E

Carlos Salas
Senior Data Scientist @ Salesloft
https://learnprompting.org/

Brandon E
Laserist @ VisionLight Events
@Carlos - thanks appreciate it!

Aditya Thiruvengadam
Senior ML Engineer @ Klarity Intelligence, Inc.
Would the presentation / video be available after this session ? Would love to go through it multiple times to try out, understand and learn!

Mark Waser
Principal @ Sciuridae Drey
Could we get a URL for that post?

Amir Jamal Kaddoura
Digital Marketer/Prompt Engineer @ WSO
@Vishal, there are many ways like defining product requirements, gathering user feedback and even product development.

Shantanu Sharma
Founder and CEO @ Stem Lending, Inc.
@Riley ― big thanks for taking the time sharing this webinar and answering the Q&A!

What trend do you foresee on the cost of model generation?

Radu Gheorghiu
Data Engineer @ Independent Consultant
@Haseeb, I am working on that summary right now. I'll share a link in a few minutes.

Jake Ottiger
Software Engineer @ Reactive Resume
@Riley can you address the instruct prompting q for ChatGPT API?

Vishal Singhania
Director, Product Management @ Medallia Inc
@amir thx. How about PM providing desired output examples with desired formats, answers etc which then would be used by Engineering to condition the model accrondingly?

Charles Frye
Deep Learning Educator @ Full Stack Deep Learning
@Vishal to original q, check out the paper on PromptChainer, it's one of the best HCI papers on prompted models
https://arxiv.org/abs/2203.06566

Vishal Singhania
Director, Product Management @ Medallia Inc
@charles thanks

Yi Ding
Programmer @ Red Oak Technologies
Alex Wang one of the best eyes for talent in the biz. 😀 Great talk!

Radu Gheorghiu
Data Engineer @ Independent Consultant
https://github.com/radu-gheorghiu/riley-goodside-scale-ai-event/tree/main

Cristiano Giardina
President @ Pattern Logic
Thank you, that was great!

Rebecca Woerner
Head of Events & Field Marketing @ Scale AI
Thanks for joining us today! We'll have the webinar available on-demand by end of day tomorrow! We'll see you at the next one!

Connor Hagen
Senior Business Development Manager @ Microsoft
Thanks, Riley.

Radu Gheorghiu
Data Engineer @ Independent Consultant
Here's a link where I'll post the chat summary & main points

David Bosnak
CEO @ Attune Media Labs
Thank you Riley!!

Fatma Tarlaci
VP of Engineering @ OpenTeams
Thank you!

Riley Goodside
Staff Prompt Engineer @ Scale
Thanks so much everyone!

John Kohlmeyer
Developer @ DriveCentric
thanks bihan for moderating

Vishal Singhania
Director, Product Management @ Medallia Inc
Thx Riley... presentation was awesome!

Jeff Choi
Business Director @ Coxwave
haha pwned!
amazing seminar!

Emily Quiles
Generalist @ None ATM
Thank you Riley!

Bihan Jiang
Product Manager @ Scale AI
Thanks for coming everyone! :)

Haseeb Mohammed
Principal Machine Learning Engineer @ Amgen
Thanks folks!

R. Brandon Cantrell
Product Analyst @ HCA Healthcare
Thanks for having this sesson!

Amir Jamal Kaddoura
Digital Marketer/Prompt Engineer @ WSO
Thanks!

Michael Lam
PM @ Speak
thanks all

David Soliven
Security Engineer @ Booz Allen Hamilton
Thank you, great to be with you all

Vivek Pandit
AI Engineer @ Microsoft
Can we also just get the presentation, apart from the recording?

Keene Do
Marketing @ Scale AI
See you at the next event!

Jorge H Cardona G
CMIO @ Analitica-MD
Thnx!!

Tony McDow
President/CEO @ Quadralay Corporation
Great job! Thank you!
Type your message...

Default Mode
Chat
Chat
Pinned Message


Rebecca Woerner
Head of Events & Field Marketing @ Scale AI
Note this talk was recorded before the public release of OpenAI’s new ChatGPT API — to learn more about how ChatGPT compares with GPT-3, check out our head-to-head comparison (
https://scale.com/blog/chatgpt-vs-davinci
) on Scale’s blog, and stay tuned for live Q&A following Riley’s talk!

Radu Gheorghiu
Data Engineer @ Independent Consultant
@Vishal, I tried this. But it halucinated quite a bit. Most of the links/articles it provided were actually fake, or at least I couldn't find them on Google / Bing.

Connor Hagen
Senior Business Development Manager @ Microsoft
@Javid did you try prompt flattering?

Charles Frye
Deep Learning Educator @ Full Stack Deep Learning
@Javid smaller models, like flan-ul2, will get that one right. If you use the formatting tricks presented here, the large models will as well.

Marc Cenedella
Founder @ Leet Resumes
@riley - thank you for your absurdly generous leadership in this space. I'm new to AI and have found it is the most welcoming, collaborative, smart, and big-hearted group of people I've ever come across, and you are at the top of that list!

Riley Goodside
Staff Prompt Engineer @ Scale
@Ana It's a rare case when the logprops of the top 2 tokens are very close — there's some computational optimization on the API. I know Boris Power (of OpenAI) gave some details about it on a Twitter thread, if you search for "deterministic" on his Twitter you'd probably find it.

Riley Goodside
Staff Prompt Engineer @ Scale
@Marc: Thank you!

Vishal Singhania
Director, Product Management @ Medallia Inc
@radu... wow fake links.. its generatring that too!

John Kohlmeyer
Developer @ DriveCentric
this is immediately before Bing chat threatened the user

Ana Ferreira
data ops @ talkdesk
thank you @riley, will do so

Amir Jamal Kaddoura
Digital Marketer/Prompt Engineer @ WSO
@Ana The behavior of a system at a temperature of zero can depend on various factors and it's difficult to determine the specific cause of the change in response without more information about the prompt and system in question.

Minsuk Kang
Software Engineer @ Scale
@riley, I might have missed the part, but do you also explain how ChatGPT persists context in a chat session? Is that done through prompt engineering?

Brandon E
Laserist @ VisionLight Events
@Javid - i just tried it and ChatGPT got it right..it stated that volume is different...

David Plon
Co-founder & CEO @ Portrait Analytics
@riley Thanks!

Riley Goodside
Staff Prompt Engineer @ Scale
@Minsuk: Essentially, yes — the process is made a bit more clear with the ChatGPT API release. There's an extension to the tokenization, but it's still technically compiled to a prompt.

Shaun VanWeelden
Field Engineering Manager @ Scale AI
Where can we hear Riley reciting more poetry?

Connor Hagen
Senior Business Development Manager @ Microsoft
we need a slow zoom-in here

Cristiano Giardina
President @ Pattern Logic
@Vishal it can't do that - but Bing Chat can, although not perfect. You can improve accuracy for a specific knowledge-base by embedding it and then performing a cosine similarity function to match your question to the correct context. In that case, you could also generate references to the relevant pages in the knowledge-base

Vishal Singhania
Director, Product Management @ Medallia Inc
Wow!

Vishal Singhania
Director, Product Management @ Medallia Inc
@Cristiano Thanks

Riley Goodside
Staff Prompt Engineer @ Scale
(I have this poem memorized btw — it's a useful party trick)

Ana Ferreira
data ops @ talkdesk
ahaha

Diego Asua
Data scientist @ BlakBear
To be ChatGPT or not to be

Vishal Singhania
Director, Product Management @ Medallia Inc
@riley haha

Britton Winterrose
Startup Solutions Architect - Y Combinator @ Amazon Web Services
Love it

John Kohlmeyer
Developer @ DriveCentric
@shaun just use elevenlabs

Cristiano Giardina
President @ Pattern Logic
Awesome

Jeff Choi
Business Director @ Coxwave
<3

David Bosnak
CEO @ Attune Media Labs
clap

Irina Poslavsky
Founder @ KoTrie
Thank you!

Marc Cenedella
Founder @ Leet Resumes
clap clap clap

Haseeb Mohammed
Principal Machine Learning Engineer @ Amgen
AWESOME

Fatma Tarlaci
VP of Engineering @ OpenTeams
@riley not only your parents, we are all very impressed I think :))

Connor Hagen
Senior Business Development Manager @ Microsoft
clapclapclap

Scott Ambler
Agile Data Coach @ Ambysoft Inc.
One of the most important uses of AI is to impress the parental units

Joe Kobrianos
Product and Tech @ Mersive
Thank you!

Brandon E
Laserist @ VisionLight Events
The only thing I can recite off by heart is Vanilla Ice, Ice Ice Baby! lol

Shaun VanWeelden
Field Engineering Manager @ Scale AI
Whoo Riley and Bihan!!

Cristiano Giardina
President @ Pattern Logic
@Riley Do you think it's possible to create jailbreak-proof LLMs without additional systems layered on top?
It seems that Anthropic's Claude is the most resilient to jailbreaking and as far as I understand is because they have a variety of systems working in concert to filter the output.
The other public-facing LLMs seem to have very simple filters on top (sometimes as simple as regex)…

Sam Ching
PM @ Duolingo
I wonder if anyone here (Riley or anyone else) has found a good way to track / measure differences in prompt output across different model versions (or providers) (chatgpt-api vs davinci-003 etc.), esp. since recent models have included prompt optimization techniques like CoT

Yi Ding
Programmer @ Red Oak Technologies
👏

Rebecca Woerner
Head of Events & Field Marketing @ Scale AI
@brandon we all have our strengths.

Charles Frye
Deep Learning Educator @ Full Stack Deep Learning
@Riley: it seems like soft prompts are not particularly popular, despite cool early results. Do you think that's because of API limitations or because of limitations to the technique?

Rebecca Woerner
Head of Events & Field Marketing @ Scale AI
Feel free to drop any questions here in the chat! And we'll funnel them to Bihan and Riley to answer

Radu Gheorghiu
Data Engineer @ Independent Consultant
ChatGPT asked me to ask you this question: "What inspired you to pursue a career as a prompt engineer at Scale AI, and what do you find to be the most rewarding aspect of your job?"

Nathan Baschez
Founder @ Lex
@sam check out
https://twitter.com/natfriedman/status/1633582489850773504

Connor Hagen
Senior Business Development Manager @ Microsoft
What are your thoughts on The Waluigi Effect? Do you think it will be a long-term concern for agentic tasks?

James Daniel
Applications Specialist II @ Wayne State University
@Riley What do you think about the anomalous tokens popularized by the SolidGoldMagikarp LessWrong post?

Sam Ching
PM @ Duolingo
Nathan - thanks! Was down ytd but will try again today!

Tim Nunamaker
Engineer @ Vana
@Riley will prompt engineering always be important as a fundamental skill, or are better models likely to mitigate the need for prompt engineering altogether?

Radu Gheorghiu
Data Engineer @ Independent Consultant
A few weeks ago I was able to get ChatGPT to only give me the response in JSON as I wanted, without the starting text. About 2-3 weeks ago, it feels like things changed and I can't get a reply without the friendly text at the beginning.

Joshua Batson
research scientist @ self
If you could fine tune or RLHF to improve GPT-K, what would you do to try to make prompting easier, or reveal more capabilities and make them easier to use?

Michael Lam
PM @ Speak
What do you think is the limiting factor that prevents GPT3 from doing math correctly? Seems like it understands logic, but not the rules of arithmetic.

Javid Lakha
Research Engineer @ Legatics
@Michael - byte pair encoding

Arjun Patel
Data Scientist @ Appen
Thanks so much for the seminar all!

Emily Quiles
Generalist @ None ATM
What are your tips to get a job in prompt engineering? I see there's a lot of talk about it, but very little jobs on the market. Is it also under another title?

Asia Butler
Front Desk Agent @ White Buffalo Club
Could prompt engineering be useful for the hospitality industry? I could see mu

Jorge H Cardona G
CMIO @ Analitica-MD
@Javid:I think that attention part of transformers has some incidence too

Asia Butler
Front Desk Agent @ White Buffalo Club
I could see multiple uses but lacking a software engineering degree leaves me confused.

Josh Pazmino
Developer @ Conscious Data
any thoughts on simulators / the waluigi effect?

Haseeb Mohammed
Principal Machine Learning Engineer @ Amgen
can someone feed this chat into chatgpt, and ask it to produce a summary of key points and questions please

Amir Jamal Kaddoura
Digital Marketer/Prompt Engineer @ WSO
@Asia of course... Automate, Automate, Automate.

Brandon E
Laserist @ VisionLight Events
For newbies to the 'prompt engineering' world, where would you recommend we go for real in-depth training (but easy-to-understand) and information on studying this fascinating new world of AI?

Touqir Sajed
AI Research Scientist @ LG Electronics Canada Inc
Awesome presentation Riley! Can you recommend us further resources on Prompt Engineering such as how industries are leveraging prompt engineering in new ways? Would be great to have a platform for industry experts to share tips and tricks on Prompt Engineering,

Javid Lakha
Research Engineer @ Legatics
@Jorge - how so? The windows are large and they have no problem writing code

Vishal Singhania
Director, Product Management @ Medallia Inc
How can Product Manager role help with optimizing prompt engineering?

Carlos Salas
Senior Data Scientist @ Salesloft
@Brandon E

Carlos Salas
Senior Data Scientist @ Salesloft
https://learnprompting.org/

Brandon E
Laserist @ VisionLight Events
@Carlos - thanks appreciate it!

Aditya Thiruvengadam
Senior ML Engineer @ Klarity Intelligence, Inc.
Would the presentation / video be available after this session ? Would love to go through it multiple times to try out, understand and learn!

Mark Waser
Principal @ Sciuridae Drey
Could we get a URL for that post?

Amir Jamal Kaddoura
Digital Marketer/Prompt Engineer @ WSO
@Vishal, there are many ways like defining product requirements, gathering user feedback and even product development.

Shantanu Sharma
Founder and CEO @ Stem Lending, Inc.
@Riley ― big thanks for taking the time sharing this webinar and answering the Q&A!

What trend do you foresee on the cost of model generation?

Radu Gheorghiu
Data Engineer @ Independent Consultant
@Haseeb, I am working on that summary right now. I'll share a link in a few minutes.

Jake Ottiger
Software Engineer @ Reactive Resume
@Riley can you address the instruct prompting q for ChatGPT API?

Vishal Singhania
Director, Product Management @ Medallia Inc
@amir thx. How about PM providing desired output examples with desired formats, answers etc which then would be used by Engineering to condition the model accrondingly?

Charles Frye
Deep Learning Educator @ Full Stack Deep Learning
@Vishal to original q, check out the paper on PromptChainer, it's one of the best HCI papers on prompted models
https://arxiv.org/abs/2203.06566

Vishal Singhania
Director, Product Management @ Medallia Inc
@charles thanks

Yi Ding
Programmer @ Red Oak Technologies
Alex Wang one of the best eyes for talent in the biz. 😀 Great talk!

Radu Gheorghiu
Data Engineer @ Independent Consultant
https://github.com/radu-gheorghiu/riley-goodside-scale-ai-event/tree/main

Cristiano Giardina
President @ Pattern Logic
Thank you, that was great!

Rebecca Woerner
Head of Events & Field Marketing @ Scale AI
Thanks for joining us today! We'll have the webinar available on-demand by end of day tomorrow! We'll see you at the next one!

Connor Hagen
Senior Business Development Manager @ Microsoft
Thanks, Riley.

Radu Gheorghiu
Data Engineer @ Independent Consultant
Here's a link where I'll post the chat summary & main points

David Bosnak
CEO @ Attune Media Labs
Thank you Riley!!

Fatma Tarlaci
VP of Engineering @ OpenTeams
Thank you!

Riley Goodside
Staff Prompt Engineer @ Scale
Thanks so much everyone!

John Kohlmeyer
Developer @ DriveCentric
thanks bihan for moderating

Vishal Singhania
Director, Product Management @ Medallia Inc
Thx Riley... presentation was awesome!

Jeff Choi
Business Director @ Coxwave
haha pwned!
amazing seminar!

Emily Quiles
Generalist @ None ATM
Thank you Riley!

Bihan Jiang
Product Manager @ Scale AI
Thanks for coming everyone! :)

Haseeb Mohammed
Principal Machine Learning Engineer @ Amgen
Thanks folks!

R. Brandon Cantrell
Product Analyst @ HCA Healthcare
Thanks for having this sesson!

Amir Jamal Kaddoura
Digital Marketer/Prompt Engineer @ WSO
Thanks!

Michael Lam
PM @ Speak
thanks all

David Soliven
Security Engineer @ Booz Allen Hamilton
Thank you, great to be with you all

Vivek Pandit
AI Engineer @ Microsoft
Can we also just get the presentation, apart from the recording?

Keene Do
Marketing @ Scale AI
See you at the next event!

Jorge H Cardona G
CMIO @ Analitica-MD
Thnx!!

Tony McDow
President/CEO @ Quadralay Corporation
Great job! Thank you!
Type your message...

LLM Prompt Engineering and RLHF: History and Techniques - Event | Scale Virtual Events
