---
layout: essay
type: essay
title: "ESLint in VSCode"
# All dates must be YYYY-MM-DD format!
date: 2025-06-27
published: true
labels:
  - Questions
  - Reflection
  - VS Code
  - ESLint
---


<h1>
Coding Standards can actually help you learn a programming language
</h1>

I do agree thay coding standards can help someone learn a programming language because in languages like Python, indentations are very vital when it comes to coding in Python.  And just having neatly written code with good indenting can not only make the code look neater, but it helps the programmer look back on the code systematically in case the programmer needs to find a bug.  For example:

```
while(strncmp(userinput, "quit", size - 1) != 0)
    {
    
        fgets(userinput,10, stdin);
        size = strlen(userinput);
        if(strncmp(userinput, "add", size - 1) == 0)
        {
            printf("\nEnter account number:");
            fgets(numinput, 1000, stdin);
            while(strtol(numinput, &null, 10) <= 0)
            {
                printf("Invalid input, try again.\n");
                fgets(numinput, 1000, stdin);
            }
```

This is a snippet of code from my ICS 212 class.  Having the code formatted like this helps makes the code more readable and whats inside a loop and such compared to:

```
while(strncmp(userinput, "quit", size - 1) != 0) {
fgets(userinput,10, stdin);
size = strlen(userinput);
if(strncmp(userinput, "add", size - 1) == 0) {
printf("\nEnter account number:");
fgets(numinput, 1000, stdin);
while(strtol(numinput, &null, 10) <= 0) {
printf("Invalid input, try again.\n");
fgets(numinput, 1000, stdin); }
```

It is immediatly more unreadable and bugs would be a lot harder to find if code was written all clumped up together like this.  And writing code this way (in C) will actually work as long as the syntax is correct.  Although it'll still work, doesn't mean we should write it this way, having coding standards helps everyone universally.  It makes it so that other people and the developer is able to read and understand how the code works and if at all, there is any problems with it.

<h2>
Impressions on ESLint
</h2>

I do think that getting rid of the errors on ESLint can be a little annoying at times, especially since I'm supposed to just put 2 spaces instead of pressing TAB to indent code.  But other than that, I think fixing the errors is actually pretty helpful and insightful, since HTML and stuff is pretty new to me.  
