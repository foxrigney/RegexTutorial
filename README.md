# RegexTutorial

## "must be a valid email address" "must contain one capital letter and one special character" 

 # have you ever seen these prompts?
 ![regex](regex.jpg)


**Welcome to the regex tutorial!**

Here we'll be discussing the definition and practical application of regular expressions or reg ex for short.

**Regular expressions** let us check our code's patterns for characters that match what we are looking for.
![regexT](regexTutorial.PNG)

Say, if you want to look for emails you'll set a regular experession looking for @ symbols and give it a parameter of having to end in .com, .org, etc.

Think of it as the "must include a valid email address" or "must contain special characters, and an uppercase"

*so lets take a specific regex, define it, and apply it*

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

this is a regular expression that matches an email


It looks like gibberish but we can break the expressions bracketed information into parts and discern what each is looking for in our strings

(each plus sign is concatinating each bracketed phrase, so its adding one specific ask after another)


`[a-z0-9_\.-]`

this is looking for characters a through z and any numbers  **ex(Foxers34)**

`@([\da-z\.-]`
this looks for digit values from 0 through 9 as well as dash marks and periods after the @ sign **ex(@spookey)**

`[a-z\.]`
matches any string value a-z and period **ex(tober.com)**

**Foxers34@spookeytober.com**



https://github.com/foxrigney


