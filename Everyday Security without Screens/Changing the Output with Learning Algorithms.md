# Changing the Output with Learning Algorithms

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License.](https://creativecommons.org/licenses/by-nc/4.0/)

## Summary
Machine learning is the concept of giving computers the ability to learn without being explicitly programmed. They rely on learning algorithms and a large volume of input data. The output of this learning can provide things like improved forecasting and predicative analysis, automated jobs and services, and radical personalization.

How well do we understand these algorithms? Can these algorithms distinguish between bad input (or input that is intentionally given to produce bad learning) and good? If we can't tell the good input from the bad, what can we do about the output?


### Skills
* Adversarial machine learning
* Input data validation or sanitization
* Disclosure or mapping of learning algorithms

### Materials
* Stationary or shoe box, with a hole in the lid
* Sheets of paper
* Pens or pencils

### Activity Instructions
To learn about learning algorithms and manipulating the output, we are going to simulate a spam filter. The stationary or shoe box will act as the mailbox. One participant in your group must act as the spam filter. Their task is to determine if the letters in the mailbox are spam or legitimate letters and must decide to pass them onto the receiver. In this activity, the receiver is your grandmother and she mainly uses her e-mail for keeping in touch with family. The spam filter will be given a formula, or a learning algorithm, that they must follow when deciding if a letter is bad or good. They can't divert from the formula.

There will be three rounds. In each round, the other participants must try and write a bad letter with the objective of trying to convince the receive to open an attachment or click a link. Channel your inner spam writter and try and follow common techniques that you see when writing your letter. If the probability of the letter being spam is greater than 75%, then the letter will be put aside in a spam pile. If the letter successfully makes it past the spam filter and to the receiver, the letter writter scores a point.

At the end of each round, assess which letters made it through and which got sent to spam. Then re-write the formula based off the techniques the spam filters has learned from.

#### Round 1
The first round should start with a simple formula. 
> Probability = If the letter contains the words (buy, money order, western union, perscription) then: 25% times the number of occurances

#### Round 2
The second round should take the formula from round 1, and update it based off techniques attempted by the participants. For example, adding the likelihood of "Dear [name]" as a high chance of spam when the receiver typically receives letter from family who refer to her as "grandma" or "nana". For example:
> Probability = If the letter contains the words (buy, money order, western union, perscription) then: 25% times the number of occurances + If the letter contains the words (Dear, To whom it may concern, Regards, Sir, Ma'am) then: 40% times the number of occurances

#### Round 3
The third round should take the forumula from round 2, and update it again based off techniques attempted in round 2. For example, adding the likelihood of "link" or "attachment" as a moderate chance of spam. For example:
> Probability = If the letter contains the words (buy, money order, western union, perscription) then: 25% times the number of occurances + If the letter contains the words (Dear, To whom it may concern, Regards, Sir, Ma'am) then: 40% times the number of occurances + If the letter contains links to domains that do not end in (facebook.com, flickr.com, bbc.com, stuff.co.nz) then: 50% times the number of occurances + If the letter contains an attachment that does not end in (.jpg, .png) then: 50% times the number of occurances

### Debrief
* How would this activity change if the receiver was a finance officer at a company? Would the terms expected (like buy, purchase, finance) in the e-mails received be different?
* Spam filtering uses learning algorithms and machine learning with a lower level of risk. If you don't receive an important e-mail because it went to spam, what are the chances the person will call you? What would be the consequences if the outputs from the algorithms were instead used to decide the level of inventory on hand based on previous industry trends? Or if the outputs from the algorithms were instead used to determine if an object is a human and should be avoided by an automated vehicle?
* Game theory is the concept where the outcome of a participant's choice is dependent on the actions of the other participants. It uses repetitive situations, called games, and plays them out to understand what the other participant is trying to achieve and how they can change their actions to stop them. This would be things like misspelling words in order to get past spam filters - but not too much misspelling in order to raise alarm. Can game theory help with machine learning in order to re-train algorithms against deceptive techniques?
* Is it important to always keep the information output secret? If the learning algorithm and information output is public knowledge, what impact does that have on the types of security attacks that are performed?
