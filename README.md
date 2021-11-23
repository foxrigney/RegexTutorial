# RegexTutorial

## "must be a valid email address" "must contain one capital letter and one special character" 

 # have you ever seen these prompts?
 ![regex](regex.jpg)


**Welcome to the regex tutorial!**

Here we'll be discussing the definition and practical application of regular expressions or reg ex for short.

Regular expressions let us check our code's patterns for characters that match what we are looking for.

Say, if you want to look for emails you'll set a regular experession looking for @ symbols and give it a parameter of having to end in .com, .org, etc.

Think of it as the "must include a valid email address" or "must contain special characters, and an uppercase"

so lets take a specific regex, define it, and apply it 

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

this is a regular expression that matches an email

It looks like gibberish but we can break it into parts and discern what each is looking for in our strings

