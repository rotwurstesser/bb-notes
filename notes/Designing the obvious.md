---
title: Designing the obvious
created: '2019-10-14T06:04:00.567Z'
modified: '2019-11-01T13:58:23.959Z'
---

# Designing the obvious

the web has three layers:

people
______ ________
interface
_______ _______
data

people want data and things, people have data and things, people wanna give them
data is the  broken down technical layer, the database, the post requests, all of it
the interdace is waht allows the people to access this, its is what we design it gives acces, it is a door to the functions, the knowledge, the thing i code and design, and the trick is to make the data accessible and usable

qualities of a great application
- it is a product of intent, it was designed and conceptualized with a clear purpose and compassion and has a purpose
- it focuses on the activity instead of the user doing it
- it only has the features needed for the users activities and doesnt confuse with random side features
- it is conform with the mental model of all users using it 
- it helps users get started quickly and teaches them by its looks, feeling and features so they get onboarded fast and become masters using it
- it stays deliberate yet ethical in nudging the user to certain actions
- it makes it hard for the users to make mistakes, yet makes it easy to correct them
- it has uniformly designed interface elements but breaks the uniform design to create meaning and importants
- it reduces clutter to a minimum

how do we build and design nice stuff?
1. know/find out what FUNCTION to build exactly
2. know what makes the FUNCTION we build great
3. know/find/experiment the best known and perceived ways of implementing said function

User centered design:
try and build personas but not too much, 3-4 are enough, having too much means you are trying to please everyone and that aint possible, define a main persona and keep in mind that this is the number 1 client, cater to their needs as best as you can
write down what they want to use the site for and what they need and use most! try and go from there : how can i give XY a good design or feature to solve his problem of not finding his favorite type of banana?
 #### Developers wanna put up textboxes and popups and shit that shows the fancy things going on behind the code, well.... users don't give a fuck, in fact they don't want to be intruded on and are confused by this, THE USERS LIVE OUTSIDE OF THE APPLICATION, THE CREATORS INSIDE

we need to aknowledge that the users goals dont have to do with the webapplication, kurt, jannick and simon only want to enter their data and be done with the work before it's 11:30 so they can go get tacos next door, trying to explain them why the server doesnt respond doesnt help, giving them a way to prepare data and upload later when it works again does!
try and design or code with empathy, think about the user, even if you and the team are far off of what the user wants, try and get into their shoes, they are not developers or designers, they are users!
but! we do not care who the users ARE we care about what they are doing! 

Another type of design is the activity centerd design:
try and find activities the users want to do or achieve and then break them down in tasks, these activitiesd can be something simple as : i want to get caught up with my mail, tasks can then be: 
1. read mail/mark as read/unread
2. delete mail
3. archive mail
4. send mail
5. respond
6. respond all

this is just one approach but there is one more player: 
Situation centered design:
people like to over estimate the PERSONAL factors in things and underestimate SITUATIONAL factors, things like where the users are from and what they do for life are often deemed more important than they situation they are in which makes people design for user profiles instead of thinkiong that they change depending on the situation: peter wants an ipod shuffle in the gym but he wants a big sound system at home... so only because he is sporty doesnt mean he will necessary buy the ipod in the store, he can, in fact, easily buy the soundsystem !

it isnt a type of person using the app, it is a person in a type of situation, think of five librarians, two are 25 year old POC, the rest is between 40 and 75, and from sweden, some play MTG, others DnD, others read norwegian thrillers in the spare time, bit they all want a good librarian application allowing them to work fast and easy!

#### apps we design are solutions for problems, problems are situational! people are not! we do not need to know who they are or what they do in the spare time! we need to know what problems they face and need to give them tools to solve it!

there was once a sandwich restaurant that wanted to add alow carb low fat option to the menu and asked people: would you order a healthier sandwich? 
people thought: oh gee if i say no i am sounding like an idiot and said yes
well... the sandwich died, no one ate it, and this shows us: ask questions that dont lead, and more importantly: that arent filled with bias, dont ask users what they want! and dont assume that users will tell you what they want! users are liars if asked outrightly (and in wrong ways)

people tend to learn one way to use an application and stick to it
people usually do these 3 things:
1. learn how it works and use it like that
2. learn 20% of the funcs cuz thry dont need more, never will
3. form their own understanding of how it works

### dont just write use cases, write exceptions, a usecase is: when the user types a message and clicks send he will send it, but an exception is when this wont happen, think what happens then, will the info get discarded? will they be able to send it later?

### add some kaizen when starting a task or writing one: do small extras and think of how they male stuff easier! did a user already fill out some infos? well then save them in a cookie, make it faster, always try and think of small improvements on every step!

Tipps to work like this:
- design a flowchart before you finish the screens, think if thos flow is how suers interact when they are in this situation
- learn how people think, not just how they look! read more books about psychology
- research situation through contextual inquiry and immersion
- skip personal details on personas! they suck! idc if betty went to harvard!
- write use cases



dont surface things up like error messages, it makes stuff harder to learn

make wireframes first, focus on the the 3 Rs:
- Requirements.  It’s easy to let a pet feature make its way into work.
Do not let things that end with "that would be nice to have" get into your product in the first round. Put them on a separate list and see what’s still important later on. If everyone still wants it, put it in. When you’re staring at your screen and drawing out all the little boxes and widgets that make up your interface, stick to your guns. Stick to what’s required. The items that are required are the most important, and therefore the only ones that should get any attention.
- Reduction. be sure to reduce as much as possible. Reduce clutter, reduce redundancy, reduce the possibility of user error,reduce, reduce, reduce. Then reduce some more. If you can find a way to make one widget serve three purposes while maintaining an obvious usage model, do it. If you can turn seven words into two, do it. If you can get rid of an entire interaction because the information it’s intended to acquire can be obtained another way, do it, do it, do it.
All of this reduction will result in a significantly more clear and usable interface. Again, remember Einstein’s rule: "Everything should be made as simple as possible, but not simpler."
- Regularity. Regularity is really about making it look like you did things intentionally. It’s about using the same font and font size for all form labels, lining up input fields so they create a consistent design, using the same spacing in all blocks of text, the same colors for similar or related interface elements, and on. Regularity means that if one text field is 20 pixels in from the left edge, and the next one is part of the same form, it should sit 20 pixels in from the left edge as well. Regularity is the notion of organizing, aligning, synchronizing, and optimizing interface elements so that they provide a clear, clean, aesthetically pleasing interface.
Of course, if you want something to pop out, you can do the opposite. Moving a single element out of line enough to look like you did it intentionally is often exactly what you need to make that element stand out from the rest of the page and show the user that this particular element is important somehow. Color can do this trick as well. If everything in your interface uses light, muted colors, you might make the Incredibly Important Note from Marketing a different color—something darker—to make it noticeable on the page. Tricks like this are used to draw the eye straight to that spot. So regularize everything that needs to look uniform, but use irregularity to communicate importance and provide additional meaning.

try the fivesecondtest on www.fivesecondtest.com : if you need a screen to be clear and concise then show a group of people the screen or page for 5 seconds and ask them to note all things they remember and saw and check if it is what you expected and wanted.

when users need to read a manual to use an application the application becomes a chore and chores arent fiun, instead of always using a tooltip to esplain stuff try using it on hover, dont ALWAYS show users a screen with 4 infos about the app, only do it on first login.

think of the principes of cialdini:
- Reciprocity: people are obliged to give back to others the form of a behavior, gift, or service that they have received first. people are obliged to give back to others the form of a behavior, gift, or service that they have received first. for example give people some discount and the ybuy more likely, even if the thing they buy is not really needed
- Commitment : people want to be seen as consinstent and trustworthy, i you get them to say: yeah ill buy, they will be very likely to buy, try and make them commit early on
- Social Proof : if others are doing it it needs to be good: for example amazon: others have also bought this, or clothing store: 1k people like this article
- Authority : if dan abramov does it then so do we... if XY is wearing it then so do we
- Scarcity : on booking-com: 0nly 5 rooms left, 10 people looking at it!
https://www.influenceatwork.com/principles-of-persuasion/


ownership: if you can give the user something, even if its trash, then do, people want to own stuff, and even if they dont need it, it makes them feel connected and they hate if its taken away

if you implement a workflow, dont forget tot draw a finish line!!! tell the user what to do in the end!!!
card sorting method :

Users are given a series of labelled cards and asked to organise and sort them into groups that they think are appropriate. Card sorting helps you to design an information architecture, workflow, menu structure or website navigation paths.
https://www.experienceux.co.uk/faqs/what-is-card-sorting/
https://www.usability.gov/how-to-and-tools/methods/card-sorting.html

MAke actions irreversible, buuild actions that forgive
users need to be able to play and try and enjoy, no fear should exist there
leverage irregularity to make elements pop out, add shadows only for special elements for example

https://medium.com/@alyjuma/the-6-principles-of-influence-how-to-master-persuasion-2f8c581da38b

1. Reciprocity
One of the most basic principles of influence is to simply give that which you want to receive. In other words, doing right by others is a good way to get others to do the same for you. This idea of reciprocity is a powerful one.
There are a couple of ways to have this reciprocity work for you. Giving others small gifts, treating others with respect, and doing favors for those in need, are all things that can win you points with other individuals.
So a good approach is to always help others and be kind when you have the opportunity, because you never know how it may help you down the line. Moreover, it is these small acts of kindness that will be remembered and come in handy when you’re in need of a favor yourself.
2. Consistency
The principle of consistency is based on the power of active, public, and voluntary commitments, which results in people actually sticking to their word. Let’s walk through these requirements in a little more detail. The first part is an active commitment. By active, Cialdini means something that is written or spoken to other’s. Having people say they will do something is a start, but when they actively commit to it they’re much more likely to follow through.
The next piece is making it public. When other’s witness this commitment, it adds a level of accountability to the statement. And no one wants to go back on their word.
Finally, it has to be voluntary. If you force someone to make an active, public commitment that they didn’t decide on themselves, you’ve accomplished nothing.
So how do you use this? Once you’ve persuaded someone to do something, get them to make these types of commitments to implement the principle of consistency and ensure there is a legitimate commitment to their words.
3. Social Proof
People rely on social cues from others on how to think, feel, and act in many situations. And not just any people, but peers. People they believe are similar to them. This is a key point and what is called social proof.
So if you wanted to influence your interns or a particular team in your department or the new hires, you need to get one of them to buy in first. When they see an employee like themselves seemingly taking action on their own or following a new directive, they are more probable to follow suit.
Having that first person take action makes all the difference and unlocks the power of social proof.
4. Liking
People like those who like them or who they perceive as friends. It’s a simple, yet powerful idea. The principle of liking can be used in a few different ways.
One method is finding common ground with the people you meet. If you can connect with them on their hobbies or interests, you’ll have a solid ground to build from. Being observant of people is a great way to pick up on any clues that may lead you to such common ground.
The other approach is genuine praise. Paying compliments and being charming can go along way to building a positive rapport with others. A word of warning though, don’t go overboard. The key here is genuine praise, don’t manufacture it to the point that you’re clearly trying to butter them up.
5. Authority
When you are perceived as an expert in an area, other’s will be more likely to defer to you. Why? Often because experts are able to offer a shortcut to good decisions that would otherwise take a long time to devise themselves. The idea then is to establish that credibility of authority and expertise.
Many often miss this opportunity because they assume others will identify their expertise automatically. You can’t leave it up to interpretation because it will often be overlooked.
There are a number of ways to establish such authority. A quick and easy one is to make visible all diplomas, credentials, and awards in the office or workplace to establish your background. Of course this may not always be an option. Another approach is to convey expertise through short anecdotes or background information shared in casual conversations.
Just remember, your expertise isn’t always a known quantity, so be sure to convey it when you get the chance.
6. Scarcity
People value what is scarce. It’s just basic supply and demand. As things become more scarce, they becoming more valuable to others. There are a few ways that you can use the principle of scarcity to persuade others. One is simply to make offers limited-time, limited-supply, or one-time, which immediately creates a sense of scarcity.
At the same time, how you present such opportunities matters too. If you focus more on loss language, or language that demonstrates what you will lose out on rather than gain, your message becomes more powerful.
Finally is the exclusivity approach. Providing access to information, services, or other items to a limited set of people creates a sense of exclusiveness. This often gets translated into being a favor to those people or that you value them more than others.
If you can combine all of these to frame a situation, your powers of persuasion greatly increase. So try to utilize limited offers, loss language, and exclusivity, to create a sense of scarcity.
Mastering these six principles of influence will enable you to maximize your abilities of persuasion. But a word of warning. Don’t abuse these skills. They can easily be used to manipulate and control others.


