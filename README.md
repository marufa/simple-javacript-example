simple-javacript-example
========================

file name js_for_in.php 
The JavaScript for...in statement loops through the properties of an object.
  To understand this example for newbies like am explain each line of this script.

      JavaScript objects are written with curly braces.
          Object properties are written as name:value pairs, separated by commas.
            The object (person) in the example above has 3 properties: fname, lname, age.
              line 10 here for (x in person) x contains the last value of the object age.
                so this loop continouing until it find the last value 
              line 11, txt += person[x]; increment and put the variable to txt until it found the last value of the   loop.
    
            output is Marufa Montaha 26
          line 13 comment consile.log(x); you can test variable x press F12 shows output age
        line 14 comment console.log(txt); test n view the output which is Marufa Montaha 26.
