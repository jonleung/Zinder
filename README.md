# Zinder

The Greek God Zeus is starting an online dating servce called Zinder. Zinder lets any users signup for a potential date with Zeus, and only zeus.

Zinder's Tagline: "Why date anyone else when you can date Zeus?"™.

We have all been hired as Zinder's first employees.


## Setup
Please open `talk.io` to your club's channel


## v0

Time to complete v0 before Zeus smite's all of us: `13 minutes`

### Step 1

Because Zinder is a luxury dating service, anyone who signs up has send in a piece of paper with their desired username and a link to their profile picture.

Zinder's developer teams (that's you) will then manually create Zinder profiles for each user with the following spec:

For example, for the data:

```
username = "jonleung137"
custom_picture = "http://i.imgur.com/eUUrzcj.jpg"
```

The website should look like this:

![image](http://i.imgur.com/oJ3bKFx.png)

Hint: To start off, create a file in [c9.io](http://c9.io) that is called `THE_PERSONS_USERNAME.html`

Hint: Make sure the above file ends in `.html`

Hint: Yes, duh, of course you will need to use Google to figure out how to make a webpage with a picture and a title if you don't know already! 

### Step 2

Once you make the simple website in step 1, use Cloud9 to host your website so that it gives you a URL that lets you see the website in your browser and anyone else's browser that is connected to the internet.

A URL may look like this:

`https://twilio-3-jonleung.c9.io/jonleung137.html`

Once you have a URL that you know works, post it in your `tlk.io` channel

Hint: Note this is a bit tricky to Google because Cloud9's documentation isn't too good. Play around in Cloud9 until you think you may find a way to get this. As soon as you find out, let your club leader know!

# v1

Before being able to proceed to step v3, everyone must have created their user profile or else Zeus will not be happy!

# v2

`BEFORE STARTING THIS CHALLENGE, CREATE A NEW WORKSPACE`

Now the challenging part, instead of having to manually add each person , Zeus wants to be able to consider ALL of facebook to be his matches instead of having people having to mail in their profile details. So, based on someone's facebook username, Zeus wants to be able to see their photo and username (like above).

My facebook username  is `jonleung137`. So Zeus wants it so that if I type in `https://PROJECT-NAME-USERNAME.c9.io/jonleung137`, he expects to be able to see this:

![image](http://i.imgur.com/Tuex18M.png)

But if he types in ***ANY*** other facebook username, he expects that it will retrieve their photo with their username as well.

This is going to be VERY HARD and it is expected that you will not finish in the time period. It is meant to push you and you are encouraged to finish at home!

HINT: Use python flask webframework.

Recommended Steps:

1. Figure out how to display someone's facebook profile picture from username. (Googling how to do this by searching for `id` instead of `username` may be helpful
2. Figure out how to even run a flask appliation on cloud9. This is a bit trickier than the normal flask instructions will tell you.
3. Figure out how to use flask to display one person's profile using flask's routing system. So getting `/jonleung137` to work
4. Figure out how to use flask's routing system to work for *ANY* Facebook username by using variable rules.

## Recap