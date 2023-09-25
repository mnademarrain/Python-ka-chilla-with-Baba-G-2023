# 1 - Heading 
<!-- to view the side pannel which is preview of the markdown file press ctrl+k=v PRESS LIKE CTRL AND LEAVE PRESS K AND LEAVE PRESS V TO VIEW THE SIDE PANNEL FOR PREVIEW REMEBER.  -->

How to give heading in markdown files?
# Heading 1
## Heading 2
### Heading 3
#### Heading ?
###### SO ON 
YOU CANNOT ADD MORE THEN THAT HEADINGS THE (HASHTAGS #)

# 2 - Block of Words
This is a normal text in markdown.

> This is a block of special text 
> 
> This is a second line
<!-- To write in 2nd line press two times Enter or add \ backword key at the end to stop that line there and go for another line 3rd add > this symbol  -->

# 3 - Line breaks

This is a 40 days long course Data Science with\
python AKA\
Python_ka_chilla_with_baba_aammar.\
This is a second line.

# 4- Combine two things

Block of words and Headings

> ## Heading 2

# 5- Face of text
**Bold**

*Italic*

***Bold and italic***

or you can use this symbols
_ (underscore)

__Bold__

_Italic_

# 6- Bullets points/ Lists

- Day-1
- Day-2
- Day-3
- Day-4
- Day-5
    - Day-5a
      - Sublist anything
    - Day-5b
- Day-6
- Day-7
  
> Numbering of lists
1. Day1
2. Day2
3. Day3
4. Day4
5. Day5
   - Day-5a
     - Sub list anything
   - Day-5b
6. Day6
7. Day7
8. Day8

 __Using *or+__    
 <!-- ab yaha pe ap * use ni ke skty bold k liye q k yaha pe * already aa rha hy is k andar to us k liye hum _(underscore) use kry gy bold k liye -->

* one
+ one

# 7 - Line breaks or page breaks

This is page 1.

---
___
***
This is page 2.
<!-- But what if we need in between lines so we goona use --- or ___ or *** -->

# 8 - link and Hyperlinks 

<https://www.youtube.com/watch?v=qJqAXjz-Rh4>
<!-- <> use the link in between these two symbols to appear as alink in prewiew this is called hyperlink -->

[the playlist of python ka chilla is here](https://www.youtube.com/watch?v=qJqAXjz-Rh4)
<!-- [] put your text inside it then () add the url after that you can see your words will become as hyperlink -->

[codanics]:https://www.youtube.com/watch?v=qJqAXjz-Rh4
<!-- another way of making kewords as link -->

This whole course is [here][codanics]
<!-- So this is the process making a targeted word as linked with any website url -->

# 9 - images and figures with link
<!-- is k liye lazim hy k ap image ko markdown k floder ma paste kry or uska name copy kry -->

To join this course please scan the Qr code and join the group or like the page or whatever the Qr code for:
![QR](QR.png)
<!-- this is how you have to add a qr image in vs code -->

online picture:

![codanics](https://www.google.com/search?sca_esv=568138803&sxsrf=AM9HkKmYFRyROslTF5VDB_SN8yfEmOfGQQ:1695632244537&q=codanics&tbm=isch&source=lnms&sa=X&ved=2ahUKEwjirOusssWBAxVih_0HHawnD8oQ0pQJegQIDBAB&biw=1707&bih=830&dpr=1.13#imgrc=GRjVtCcWAILqOM)

<!-- for online pictue ap ny pehly keyword bnana hy usy [] is k andar likhna hy then () is k andar ap ny kici b online picture ka url dena hy or keyword k pehly jese he ap ! ye sign lgay gy to lazim hy k file thora sa time ly kr generate ho jay ge prewiew ma or jese he is sign ko ! remove kry gy file show ni ho ge or just keyword show ho ga as a lik -->

# 10 - Adding code or code block

To print a string use `print("codanics")`

`print("baba G)`

```
x = 5+6
y = 3-2
z = x+y
print(z)
```
<!-- to ye hy ap ka g block of code 
is ka faida ye hy k jub b ap ny string likhna hy to uper diye gy `` sign k andar likhy after the code or agr zyada tareekay sy likhna hy to ``` ``` is tra k sign lga kr in k middle ma likhy or preview ma ye block type kikha jay ga plus github pr b is k corner pr apko alag sy copy ka option mily ga-->

> This Code with show color according to Python language syntax

```python 
x = 5+6
y = 3-2
z = x+y
print(z)
```
> This Code with show color according to R language syntax
<!-- this is how you can seprate the block of code while adding the such lie or details of the code. -->

```R 
x = 5+6
y = 3-2
z = x+y
print(z)
```
<!-- ab is murad k ap dono ka color dekh lo different hy bco ap ny use of language add kiya hy 2nd waly block of code ma or ici tra hr language ka sign ap likh skty hy or multi color dekh skty hy ya fr unka style apply kr skty hy # just writing the language name right after ``` this sig in start as its showing up there in python language -->

# 11 - Adding tables

| 
<!-- Tables bnany k liye apko ye pipe ka sign use krna hy always it will show right up of the Enter button on your keyboard press Shift+that button to avail this -->

| Species | Petal_length | Sepal_lenght|
| ------- | ------------ | ----------- | 
| Verginica | 18.2 | 19.2 | 
| Satosa | 15.1 | 17.2 | 
| Versicolor | 12.2 | 12.2 | 
| Verginica | 18.2 | 19.2 | 
| Satosa | 15.1 | 17.2 | 
| Versicolor | 12.2 | 12.2 | 

<!-- This is how you will make the graph or table while use of | - these signs-->

<!-- Now one more thing: jisy hum kehty hy k alignments (middle) (right side) or (left side) same as ms xl or ms word to us k liye hum : (colon) is sign ka use kry gy kesy watch down-->

| Species | Petal_length | Sepal_lenght|
| -------: | ------------: | -----------: | 
| Verginica | 18.2 | 19.2 | 
| Satosa | 15.1 | 17.2 | 
| Versicolor | 12.2 | 12.2 | 
| Verginica | 18.2 | 19.2 | 
| Satosa | 15.1 | 17.2 | 
| Versicolor | 12.2 | 12.2 | 

> # Right Aligned

<!-- This : (colon) agr ap code k right side jaga pr dy gy to it will be right align ho ga -->

| Species | Petal_length | Sepal_lenght|
| :------- | :------------ | :----------- | 
| Verginica | 18.2 | 19.2 | 
| Satosa | 15.1 | 17.2 | 
| Versicolor | 12.2 | 12.2 | 
| Verginica | 18.2 | 19.2 | 
| Satosa | 15.1 | 17.2 | 
| Versicolor | 12.2 | 12.2 | 

> # Left Aligned

<!-- This : (colon) agr ap code k left side jaga pr dy gy to it will be left align ho ga -->

| Species | Petal_length | Sepal_lenght|
| :-------: | :------------: | :-----------: | 
| Verginica | 18.2 | 19.2 | 
| Satosa | 15.1 | 17.2 | 
| Versicolor | 12.2 | 12.2 | 
| Verginica | 18.2 | 19.2 | 
| Satosa | 15.1 | 17.2 | 
| Versicolor | 12.2 | 12.2 | 

> # Middle Aligned

<!-- This : (colon) agr ap code k left + right sides jaga pr dy gy to it will be middle align ho ga --> 


<!-- Abi hum ny is sub codes ya kaam k headings ya fr keh lo k contant bnany hy to wo kch is tra sy bany gy its like same he page pr ap headings likhty hy last ma ya side ma kici b blog ka shortcut to reach that faster chahy wo kici b page pr ho -->

# 12 - content

[1-Headings](#1---heading)\
[2-Block of Words](#2---block-of-words)\
[3-Line of Breaks](#3---line-breaks)\
[4-combine two things](#4--combine-two-things)\
[5-face of Text](#5--face-of-text)\
[6-Bullets Points](#6--bullets-points-lists)\
[7-Line Breaks](#7---line-breaks-or-page-breaks)\
[8-Link and Hyperlinks](#8---link-and-hyperlinks)\
[9-Images](#9----images)\
[10-Adding Code or block of codes](#10---adding-code-or-code-block)\
[11-aligments](#11-----alignment-)\
[12-adding talbles](#11---adding-tables)

# 13 - install extensions 
Markdown PDF\
Mardown Shotcuts\
Markdown lint

> Extension krny ka faida ye hy k ap koi b text likhy then us k uper right click kry to bohat sary options mil jaty hy jisy ap easily use kr skty hy
----- 
> # as example making tables bold italic converting while file into pdf jpeg png htm adding image adding links wxtra extra extar.

![image](QR.png)
