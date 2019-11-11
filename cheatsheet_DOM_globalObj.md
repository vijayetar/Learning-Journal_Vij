# DOM #
- document.title = tile of document
- document.lastModified = date when last modified
- document.URL = string containing URL
- document.domain = returns domain of current document
- document.write() writes text
- document.getElementById() gets element
- document.querySelectorAll() returns list of elements that match CSS selector
- document.createElement() creates new Element
- document.createTextNode() creates new text node
----

# String Object #
Example:
- var string = 'Home Sweet Home'
- string.length; = 14
- string.toUpperCase()
- string.toLowerCase()
- string.charAt(12) = 'o'
- string.indexOf('ee') = 7
- string.lastIndexOf('e')= 14
- string.substring(8,14)= 'et hom'
- string.split('') = ['Home','sweet','home','']
- string.trim(); = removes white space at start and end of string
- string.replace('me','w')= 'How sweet home'

# Using date Object (and Time) #
- First create instance of the date object by using var and then review the different methods available
- var today = new Date();
- today.getDate() = returns day of the month
- today.getDay() = returns weekday
- getFullYear() = year (4 digits)
- getHours() = hours (0-24)
- getMinutes = min (0-59)
- getMilliseconds()= ms(0-999)
- getMonth()= month(0-11)
- getTime()= number of milliseconds since Jan 1, 1970
- getTimezoneOffset()
- toDateString() - returns date as a readable string
- toTimeString() - returns time as a readable string
- toString() returns a string representing the specified date

[Return to homepage](README.md)