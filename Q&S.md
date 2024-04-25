# 1.What are the variables naming conversions in javascript?
### Ans: -Variables are case sensitive.
### -Variables can be single chracter or multi character or alphaneumeric.
### -Space are not allowed in variable names,
### -Only letters, digits, underscores and dollar signs are premitted in variable names.
### -Case matters when it comes to variable names.
### -A letter(Alphabets), an underscore(_), or a dollar sign($) must be the first character in a variable name, any other special characters mut not be taken.
### -Certain terms such as reserved words in javascript shouldn't be used to name variables.

# 2.Create a greeting alert ?(use => promt, message, alert)
` let yourName=promt"Enter your name"
 alert("Hellow"+" "+yourName+"!"+" "+"Welcome"+""+"to"+""+"our"+""+"website.")`

# 3.Write some code so that the values of the below variables switch around?
## Let fish="fly", let bird="swim". Switch the value so that fish holds the value "swim" and the variable bird holds the value "fly"
`let fish=fly;
 let bird=swim;
 let c=bird
 bird=fish
 fish=c
 console.log("fish=" +fish)
 console.log("bird=" +bird)`