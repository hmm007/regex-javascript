# Method

from Mozilla Developer Network [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)

###exec 	
A RegExp method that executes a search for a match in a string. It returns an array of information.
###test 	
A RegExp method that tests for a match in a string. It returns true or false.
###match 	
A String method that executes a search for a match in a string. It returns an array of information or null on a mismatch.
###search 	
A String method that tests for a match in a string. It returns the index of the match, or -1 if the search fails.
###replace 	
A String method that executes a search for a match in a string, and replaces the matched substring with a replacement substring.
###split 	
A String method that uses a regular expression or a fixed string to break a string into an array of substrings.

#Flag

###g  
global matching 	
###i 	
ignore case 	
###m 	
multiline input

#Meta & Shorthand Characters

##^ 	
/^anyword/ 	start with
##$ 	
/anyword$/ end with
##* 	
/anyword*/ 	
+ 	
	/anyword+/ 	
? 	
/anyword?/ 	
. 	
/.anyword/ 	
\ 	
/4\.0/ 	
(...) 	
/(anyword) \1's/ 	
(?:...) 	
/(?:anyword) \1's/ 	
(?=...) 	
/anyword(?='s)/ 
(?!...) 	
/anyword(?!'s)/ 	
...|... 	
/anyword|anyword/ 	
{...} 	
/anyword{2}/ 	
{...,} 	
/anyword{2,}/ 	
{...,...} 	
/anyword{2,4}/ 	 
[...] 	
/[anyword]|[anyword]/ 
[...-...] 	
/[a-z]|[0-9]/ 	
[^...] 	
/[^a-z]/ 	

##Shorthands
\b 		
\B 		
\d 		
\D 	
\s 	 	
\S 		
\w 		
\W 	
