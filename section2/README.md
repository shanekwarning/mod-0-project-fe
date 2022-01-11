# Section 2 - GROWTH MINDSET, Conditionals and Functions

Section 2 is estimated to take a total of 6-8 hours to complete. Similar to Section 1, this section of the project involves reading (both from this document as well as the 📒John Duckett book), 👨🏽‍💻exercises, and 📝reflection questions. Make sure to manage your time well so that should you get stuck and need help, you have plenty of time to do so and meet the deadline.

- [Vocabulary](#vocabulary)
- [Get Set Up](#get-set-up)
- [Part A: Growth Mindset](#part-a-growth-mindset)
- [Part B: Conditionals](#part-b-conditionals)
- [Reflections](#reflections)
- [Commit Your Work in Git](#commit-your-work-in-git)
- [Push to GitHub](#push-to-github)
- [Vocabulary From Book](#vocabulary-from-book)

## Vocabulary

This section will introduce a number of new terms, that may feel a bit more complex. Write these terms and reserved keywords in that special spot in your notebook now. Work to hold yourself accountable to updating definitions _as you work through this section_.

### Vocabulary Terms

- comparison operators
- logical operators
- condition
- conditionals
- if statements

### JavaScript Reserved Keywords

- `if`
- `else if`
- `else`

## Get Set Up

Using the Terminal, open the local copy of the repository that you created during setup.  To do this, you will need to use the terminal command `cd` to change into the directory that holds the repository. Once you are in the correct directory, use the terminal command `atom .` to open the project repository. If you are having trouble with this, see the `section1` instructions.

## Part A: Growth Mindset

Read/watch one or both of the following:

- This [2-part blog post series](https://blog.mindsetworks.com/entry/how-having-a-growth-mindset-can-help-you-learn-to-code) discusses how having a growth mindset is helpful when learning to code, and how coding promotes a growth mindset!
- This [video interview](https://dev.to/hackflix_dev/how-to-hack-a-growth-mindset-b1g) where an experienced Front End engineer discusses learning about the concept of Growth Mindset and how that's changed how she sees her work and career. (The first 7 minutes are intros and a discussion on Developer Relations. After that, the conversation about Growth Midnset begins.)

Then, consider on the following questions. We will ask you to share some of these responses at the end of this section.

- What are two points from the article or video that either resonated with you, or were brand new to you?
  - One point that resonated with me is "Challenge Seeking". The line that I related to the most was "Without a challenge, there is not work to be done". I feel like in my current career that I will be leaving soon, I have not had a challenge in years. It has become stagent and it becomes harder and harder each day to continue to work. A challenge keeps things fresh and exciting. If there is not anything new to learn, see, or explore it takes the joy out of the work and the reward.
  - The other part that resonated with me is also from the article. It stated to push beyond your level of understanding little by little. I find this extremely important for me to make this statement part of me. I often try to take on too large of task/learning to much at once and find myself struggling and losing hope. I have already started to do this during the sessions so far as well as when I work on the homework and the project here. If I come across something that feels like it is extra and may not directly pretain to completing the task at hand or if it is additional information ontop of the root information during class I do not fret over it and instead focus on the primary material. At this time the "little by little" is just the core information needed to pass Mod0.


- In which ways do you currently demonstrate a Growth Mindset? In which ways do you _not_?
- Currently I find myself demonstrating Groth Mindset with the example I provided above. I am learning little by little and taking each challenge as it comes in bit size digestable pieces.
- Way I do not practice Growth Mindset is practing. I have had trouble to get myself to practice in my life. I have already seen the need during this program and recongize that each of our assignments so far has lots of repeat steps to have us do things over and over again. It is working because I have picked up on many of the lessons and can come back the next day without having to look up how to complete a task I learned how to do the previous day.
- Time management I think will be another area I will work on and hone thoughout the program. This pairs with pratice. Practice takes time, so does the program, my dog, hobbies, family. Everything takes time and when its not scheduled things get missed and left unattended. Setting time and utilizing a calendar even for just this week of class has shown the power of time management.

- What is something you are good at or knowledgeable at now, that you once weren't? How did you get those skills/knowledge? Was it hard at some point?
- For the past three years I have worked at painting miniatures for different table top games. I did not know where to start at first and it inhibited me for many years. At first it was difficult and took alot of time to paint them even to get them to a basic standard. I now have been commissioned to paint for people, have one a painting contest, and can paint faster than anyone else in my gaming group. I learned this from youtube, from talking to other experienced painters in the community, and most of all putting in pratice, trying new techniques and pushing myself to learn more and more each time I picked up the paint brush. After typing this out I can really see how the Growth Mindset applies.

## Part B: Conditionals

One of the most important concepts in programming is knowing when and how to tell the computer to do either _one_ thing or _another_ thing based on a set of simple criteria.  We can accomplish this with if statements, which you will learn about in this section.

When you are all done with the lessons, exercises, and reflection for this section, you will once again use Git to save your work, and then put it in the cloud on GitHub.

### Operators

When you learned about Booleans in Section 1, you briefly read about and practiced using some comparison operators.

The conditional operators we touched on earlier are critical in the set up of if statements. Conditional statements (conditions) evaluate to `true` or `false`. The most common operators used for conditions are comparison operators:

* `===` (strictly equal)
* `!==` (not equal)
* `>` (greater than)
* `>=` (greater than or equal to)
* `<` (less than)
* `<=` (less than or equal to)

Some data types also have functions which return a `true` or `false`, so they’re used in conditional statements. We will touch on those later in the project and when you get into Mod 1.

- Read more about [comparison operators here](https://javascript.info/comparison)
- Read about [logical operators here](https://mariusschulz.com/blog/the-and-and-or-operators-in-javascript). You really just need to read the top first paragraph and code snippet in this post. You'll go deeper in Mods 1-2.

> 👨🏽‍💻 PAUSE here, and complete the exercises in `comparisons.js`

### If Statements

📒 Read pages 148-149 and 160-163 from the `JAVASCRIPT & JQUERY: Interactive Front-End Web Development` book. If you are unsure of some vocabulary you encounter, refer to the [vocabulary list](#Vocabulary-From-Book) at the end of this README.

In addition to **`if`** and **`else`**, **`else if`** can help us create more complex statements. `else if` statements execute a block of code when their condition **evaluates** to `true`. However, they must be chained to a previous `if` statement, like so:

```javascript     
if (condition1) {
    //block of code executes if condition1 evaluates to true
} else if (condition2) {
    //block of code executes if condition1 evaluates to false and condition2 evaluates to true.
} else if (condition3) {
    //block of code executes if condition1 and condition2 evaluate to false
    //and condition3 evaluates to true.
} else {
    //block of code executes if none of the conditions above evaluate to true.
};
```

### If/Else Statements

Why do we have conditional statements? Most often it’s to control conditional instructions, especially *if/else if/else* structures. Read the following code snippet, then the accompanying explanation that follows it.

```javascript
var minutesToHeatWater = 7;

if (minutesToHeatWater < 7) {
    console.log("The water is not boiling yet.");
} else if (minutesToHeatWater === 7) {
    console.log("It's just barely boiling");
} else if (minutesToHeatWater === 8) {
    console.log("It's boiling!");
} else {
    console.log("Hot! Hot! Hot!");
};
```

What would be logged when `minutesToHeatWater` is 7? What if we changed it to 5? Or 8? Or 9?

- When the `minutesToHeatWater` is 5, here is how the execution goes: "Is it true that 5 is less than 7? Yes, it is, so print out the line The water is not boiling yet.".
- When the `minutesToHeatWater` is 7, it goes like this: "Is it true that 7 is less than 7? No. Next, is it true that 7 is equal to 7? Yes, it is, so print out the line It's just barely boiling".
- When the `minutesToHeatWater` is 8, it goes like this: "Is it true that 8 is less than 7? No. Next, is it true that 8 is equal to 7? No. Next, is it true that 8 is equal to 8? Yes, it is, so print out the line It's boiling!".
- Lastly, when `minutesToHeatWater` is 9 or greater, it goes: "Is it true that 9 is less than 7? No. Next, is it true that 9 is equal to 7? No. Next, is it true that 9 is equal to 8? No. Since none of those are true, execute the else and print the line Hot! Hot! Hot!".

Only one section of the *if/else if/else* structure can have its instructions run. If the *if* is true, for instance, JavaScript will not bother to look at the *else if* or *else*. Once one block executes, that’s it.

### Equality vs. Assignment

The **number one mistake** people encounter when writing conditional statements is the difference between `=` and `===`.

* `=` is an assignment. It means "take the value on the right side and store it into whatever is on the left side" – it’s telling, not asking.

* `===` is a question. It means "is the value on the right the exact same as the value on the left?" – it’s asking, not telling.

> 👨🏽 ‍💻PAUSE here, and complete the exercises in `decision-making.js` and `if-statements.js`

## Reflections

📝 Answer the prompts in the `reflection.md` file in the `section2` directory. If you need a reminder on how to format your markdown, [this is the Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)!

## Commit Your Work in Git

When you are finished with all of the `section2` activities, use the Terminal to run the following commands in order to save your work to your local Git repository.

1. `git add section2/exercises`
2. `git add section2/reflection.md`
3. `git status` - you should see only green filenames - if you see any that are red, continue to `git add` those files until `git status` shows all green files.
4. `git commit -m "Add Section 2 work"`

## Push to GitHub

You've saved your work to Git on your local machine, but your repository on GitHub doesn't reflect it yet. You update the remote GitHub repository with your new local commits when you `push` your changes.

Run:


```
git push origin main
```

You should now be able to log in to GitHub, navigate to your remote project repository and see all the work you did in this section!

## Vocabulary From Book
The readings in the `JAVASCRIPT & JQUERY: Interactive Front-End Web Development` book use JavaScript in a way that is likely unfamiliar to you. The book uses specific JavaScript properties and functions to interact with HTML elements on a webpage, like changing or adding text on a webpage. Initially, we will be using JavaScript without HTML. That's why you haven't seen these techniques before! We will address these techniques thoroughly during Mod 1, however, here are some quick definitions to help you become familiar with them.

* `document.getElementById()`: a method used to retrieve an element from a web page. Here is the [MDN documentation](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)
* `document.write()`: a method used to write data to a webpage. Here is the [MDN documentation](https://developer.mozilla.org/en-US/docs/Web/API/Document/write)
* `el.innerHTML()`: a method used to change the text of an element *(defined as the variable el)* from a web page. Here is the [MDN documentation](https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML)
* `el.textContent()`: a method used to change the text of an element *(defined as the variable el)* from a web page. Here is the [MDN documentation](https://developer.mozilla.org/en-US/docs/Web/API/Node/textContent)

***

🚀 [Go to Section 3](../section3)
