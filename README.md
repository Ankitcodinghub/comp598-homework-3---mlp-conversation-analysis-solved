# comp598-homework-3---mlp-conversation-analysis-solved
**TO GET THIS SOLUTION VISIT:** [COMP598 Homework 3 – MLP Conversation Analysis Solved](https://www.ankitcodinghub.com/product/comp-598-homework-3-mlp-conversation-analysis-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118608&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP598 Homework 3 – MLP Conversation Analysis Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
The goal of this assignment is for you to develop python scripts and code using best practices covered in the lessons this week to conduct a complete a data analysis project on My Little Pony. Note that all work for this homework must be done in python.

Task 1: Watch some My Little Pony episodes (0 pts – totally optional)

It’s always important to study your source material … particularly when it’s very entertaining cartoons!

Task 2: My Little Pony dialog analysis (20 pts)

We’ll be using the dataset available here: https://www.kaggle.com/liury123/my-little-pony-transcript

For the purpose of this study, we’ll use only clean_dialog.csv and assume that the dataset is perfect.

Write a python script named analysis.py that, when run, computes and produces a JSON-formatted analysis of the ponies’ interpersonal dynamics that has exactly the structure given below (all numbers below are just examples). The canonical pony names used in the file should be: twilight (Twilight Sparkle), applejack (Applejack), rarity (Rarity), pinky (Pinky Pie), rainbow (Rainbow Dash), and fluttershy (Fluttershy). All other characters are considered “non-Pony” characters.

{

“verbosity”: { // give fraction of dialogue, measured in # of speech acts produced by this pony

“twilight”: 0.37,

“applejack”: 0.24, …

},

“mentions”: { // give fraction of times each pony mentions the other

“twilight”: { // the fractions here should sum to 1

“applejack”: 0.12, “pinky”: 0.51,

…

}, …

},

“follow_on_comments”: { // the fraction of times each pony has a line that DIRECTLY follows the others pony’s line

“twilight”: { // the fractions here should sum to 1

“applejack”: 0.21,

…,

“other”: 0.4 // this is the number of times TS has dialogue following a non-Pony character

}, … }

“non_dictionary_words”: { // a list of the 5 non-dictionary words used most often by each Pony

“twilight”: [ “huh”, “ugh”, “awwww” , “wheee”, “wha”] …

}

}

– Here a “word” is any substring bordered by non-alphanumeric characters OR the start/end of the containing string. This means that “anti-aircraft” contains the words “anti” and “aircraft”.

– A pony mention occurs when any of the words composing that pony’s name appears in dialog, with that word capitalized. So “Hey Twilight!” counts as a mention of Twilight Sparkle. “I like pie” does not count as a mention of Pinky Pie because “pie” is not capitalized.

– Non-dictionary words are any not present in the list words_alpha.txt, located here:

https://github.com/dwyl/english-words o This should be saved in your project as data/words_alpha.txt

Task 3: Unit Testing (5 pts)

Write at least 10 unit test (10 functions) for your code spread across mentions, follow-on-comments, and nondictionary words. They must all pass.

Submission Instructions

Your MyCourses submission should contain a project with the following structure

– scripts/ o analysis.py

 This should use argparse and print a helper message when no arguments are given.

 This should accept the link to the clean_dialog.csv.

 It should assume that words_alpha.txt is sitting in the data/ directory.

 It will be run in a UNIX shell in which PYTHONPATH includes a path to the project’s src directory. This will allow it to use code in the hw2 package.

 It should accept an optional argument “-o &lt;file_name&gt;”. If given, the JSON output is written to that file. If it is NOT given, the JSON output should be written to stdout. – data/ – this directory is empty. Do NOT submit your dialogue or words files. When graded, the TAs will provide these.

o Nothing in this directory.

– src/ o hw2/

 &lt;code&gt;

 test.py – this runs all your unit tests. At least 10 must be run and succeed.

 tests/ – this directory contains your unit tests
