# Regrex Fun facts

##### Allows you to search through text and even group them toether to find and replace

##### Expressions always normally start '/' and also end with '/'

##### There are couple tags each expression can get 
G global ~ Inside the // the fucntion will search and pull out everything matching inside 
I Case insenitive ~  So it looks at the exact thing that was typed in bewteen the // and pulls it out of the string 

##### Another cool thing that you can do is look for specific letters 
/e+/ is going to all the places of single letters e and also words that two or more e in example strEEt 

/ea?/ is still going to give you all the single letters of e in the array but will also look for words that have ea in order in example sEArch

/ea*/ is the mix between both which means the a is only optional if it falls after an e and also searches for any repeating e 

/.at/ the period is very important as it allows you find any character in example words like Bat Cat Eat Fat Nat it will match anything but a new line 
/\./ the back slash allows you to escape a charcter not normally used in order to find and replace 

/w/ pulls out any words in the string 

/s/ pulls out any white space in the string 

/\w{3}/ means you can search any 3 letter words  # Regex-Tutorial
