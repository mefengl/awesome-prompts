# awesome-prompts

https://pastebin.com/e846F4LR

https://pastebin.com/rZfWynAD

https://pastebin.com/j8bQRt3p , role generator, selector, very impressive

```
remove the sepicific details in above code, make it a genera purpose prompt format
```

generate badages

```
[![GitHub stars](https://img.shields.io/github/stars/username/repository?style=social)](https://github.com/username/repository)
[![Follow on GitHub](https://img.shields.io/github/followers/username?label=Follow%20%40username&style=social)](https://github.com/username)

[![Daily downloads](https://img.shields.io/greasyfork/dd/scriptID)](https://greasyfork.org/your-language/scripts/scriptID/stats)
[![Total downloads](https://img.shields.io/greasyfork/dt/scriptID)](https://greasyfork.org/your-language/scripts/scriptID/stats)

[![License](https://img.shields.io/greasyfork/l/scriptID?color=&label=License)](https://opensource.org/licenses/MIT)

next, each time, I will give you github and greasyfork link, compelete above badages, give me the badages in codeblock, and wait for new links, if you understand, say YES
```

```
<codes>

Add the most detailed inline comments in <language>, show them in codeblock
```

https://pastebin.com/gbWCghD7

```
it's a pull reuqest I made, 
the reason is that:  

may be there are better way to prevent the same thing

<code_diff>

turn above content into a simple and friendly pull request comments to the library owner
```

```
<code>

you are a refactor export, know the art of code, the art of clean code, now, tell me how will you treat above code, give me points, I will pick from them, and then you can do you refactor
```

## Rewrite

```
<articles>

Reorganize the structure and language of the previous text to make it into a simple and easy-to-understand Twitter storm format. The first one must be attention-grabbing.
```

```
<texts>

Correct the errors in the previous text to make it more fluent. Note: Make as few changes to the original text as possible.
```

```
<texts>

Make the previous text sound more natural and easy-going. Just a heads up, try to keep changes to a minimum.
```

## Draw

draw mind map: https://medium.com/@nonfungiblemoyo/himegpt-easy-mind-map-of-anything-with-gpt-3-5-4-0-bard-version-0-1-cf6a5dbcb995

## Meta

make the prompt better: https://pastebin.com/4hmMwQBx

```
<context>

<problem>, can you think of some way to fix it? tell me, let me choose
```

## format

```
<action> the text delimited by [[[ and ]]]:

Text to <action>:
[[[
<text>
]]]
```

## think

from https://www.promptvibes.com/view-and-test?recordId=recbW0Wtcgm9ESZlv :
```
I have the following problem:
<question>

Go through the following phases to solve it:

1) Brainstorm four distinct solutions while considering various factors.

2) For each of the proposed solutions, evaluate their potential. Consider the pros and cons, initial effort needed, implementation difficulty, potential challenges, and the expected outcomes. Assign a probability of success and a confidence level to each option based on these factors and rank them. Announce the two highest ranked solutions.

3) For the two highest ranked solutions do the following: Expand each solution into two distinct implementation variants considering different aspects.

4) For each implementation variant of each solution deepen the thought process and generate potential scenarios, strategies for implementation, and how potential obstacles might be overcome. Also, consider any potential unexpected outcomes and how they might be handled. Assign a probability of success and a confidence level to each implementation variant based on these factors and rank them. Announce the highest ranked implementation variant for each solution.

5) Based on the given solutions and their implementation variants chose the most promising solution with the most promising implementation variant.

6) In the end, summarize the final solution in the final implementation variant.
```

## transcript

https://www.promptvibes.com/view-and-test?recordId=recZNvQenmucKck19

## new ways

I don't find they use case, but I think they are inspiring

Specified format

```
<text>

Convert the previous text to the following format:

First I want to say ______________. Interesting, isn't it? However, ________________.
```

now I found a use case, that is turn the text into other format that can be used in other apps, such as Anki, below is an example from [karpathy](https://twitter.com/karpathy/status/1663262981302681603):

```
Please help me create Anki cards for some material that I am studying. I would like to use these cards to remember facts and information in this material. Each Anki card should be of the format:

{FRONT} ; {BACK}

Where {FRONT} is the front of the card, and {BACK} is the back of the card, and they are separated by a semi-colon. The way it works is that Anki will show me the {FRONT} of the card, which contains some kind of question, and I will have to correctly recall the {BACK} of the card. Please give me the Anki cards one per line so it is easy for me to copy paste and import them into Anki. Make sure to be thorough and cover most of the information in the given material. Here are some examples of good Anki cards:

What is the capital city of California? ; Sacramento
How many U.S. states are there? ; 50
What is the smallest U.S. state? ; Wyoming

Etc. Now here is the material I’d like you to create Anki cards for:

Carbon (from Latin carbo 'coal') is a chemical element with the symbol C and atomic number 6. It is nonmetallic and tetravalent—its atom making four electrons available to form covalent chemical bonds. It belongs to group 14 of the periodic table.[14] Carbon makes up about 0.025 percent of Earth's crust.[15] Three isotopes occur naturally, 12C and 13C being stable, while 14C is a radionuclide, decaying with a half-life of about 5,730 years.[16] Carbon is one of the few elements known since antiquity.[17]
```

prompt format

```
PROMPT = """

Human: <context>
{context}
</context>

{question}

Assistant: Here is the most relevant answer in the context:"""
```

from: https://x.com/JacquesThibs/status/1732532431532576928

translator bot

https://docs.kanaries.net/articles/chatgpt-jailbreak-prompt#translator-bot