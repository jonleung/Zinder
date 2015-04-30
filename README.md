# The One Book of Faces To Rule Them All!!!

<!--![image](http://i.imgur.com/Uz5B5c5.jpg)
-->
Middle Earth is finally at peace and Gandalf decides to start a social network startup: The Book Of Faces.

We have all been hired as The Book of Face's first employees!

## V1 - Manual Website Creation

We will all be working in same c9.io workspace

**Setup:**

1. Go to `bit.ly/book-of-faces`
2. Login to your c9 account
3. Click "Request Access"
![image](http://i.imgur.com/Xl9f3EI.png)

**Your Job**

Users register for The Book Of Faces by sending in a piece of parchment with their username desired.

When you get a piece of paper, your job is to:

1. Find an appropriate profile picture of them *(your users are very trusting)*
2. Based on their username, create a simple webpage that 

	- is reachable at `https://book-of-faces-jonleung.c9.io/USERNAME.html`
	- displays their profile picture
	- displays their username
	
**Example**

So for example, if you got a piece of parchment that said `"username: gmoney"`
![image](http://i.imgur.com/e9LlqqX.png)

- you would be able to reach it at `https://book-of-faces-jonleung.c9.io/gmagic.html`
- the site displays a profile picture
- the site displays the username, `"gmagic"`

**Objective**

Your objective is to help as many users signup as possible! When you've signed up your first user, post into the tlk.io with the link to their profile.

**Hints**

Hint: To start off, create a file in [c9.io](http://c9.io) that is called `THE_PERSONS_USERNAME.html`

Hint: Make sure the above file ends in `.html`

Hint: Yes, duh, of course you will need to use Google to figure out how to make a webpage with a picture and a heading if you don't know do it already!

```
Create A List Of Teams That Have Published On Whiteboard
```

## V2 - Dynamic Website Creation

![image](http://i.imgur.com/PBmGh9O.png) 

Congratulations, due to your hard work, Facebook has now purchased The Book of Faces for 19 Billion dollars. Now it is your job to incorperate every facebook user into into the Book of Faces application!

But manually creating more than 1 billion users is hard...

**So now What?**

So now the challenging part, instead of having to manually having to add every Facebook user, Gandalf wants automatically add EVERY facebook user to The Book of Faces based on their Facebook username.

My facebook username  is `jonleung137`. So if Gandalf types in `https://PROJECT-NAME-USERNAME.c9.io/jonleung137`, he expects to be able to see this:

![image](http://i.imgur.com/Tuex18M.png)

But if he types in ***ANY*** other facebook username, he expects that it will retrieve their photo with their username as well.

This is going to be VERY HARD!

**Let's Look At How Facebook Works**

In the below steps, you will be learning how to build your own server! Let's learn about how Facebook's servers work.

**Setup**

1. Before starting this new challenege, create a new Cloud9 workspace.

## Steps

**Step 1**

Figure out how to display someone's facebook profile picture from username. (Googling how to do this by searching for `id` instead of `username` may be helpful.

Test in your browser if you can retrieve your own profile picture or my profile picture based on  our usernames `jonleung137`.

**Step 2**

Python flask is a server, that "real" people use including Pinterest, Twilio, Reeddit, and Barak Obama's 2012 campaign. Figure out how to even run a very basic python flask appliation on cloud9. Running it on cloud9 is a bit trickier than the normal flask instructions will tell you. 

*HOW DID I KNOW?*—http://www.quora.com/What-is-the-largest-site-created-using-Flask

Let's make sure we understand what's happening here.

**Step 3**

Figure out how to use flask to display one person's profile using flask's routing system. So try getting `/jonleung137` to work using your knowledge from step 1

**Step 4**

Figure out how to use flask's routing system to work for *ANY* Facebook username by using variable rules.

So you want to be able to type in mine username, `/jonleung137`, Mark Zuckerberg's `/zuck`, or Obama's `/obama`.

This is predominantly the cool part about using a server like Flask, it let's you create a dynamic response as opposed to using static HTML files.

## Recap

What's a server?

What can you do with a server?
