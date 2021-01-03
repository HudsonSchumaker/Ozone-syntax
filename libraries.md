Built in functions on O³ programming language

Strings.o library

@include String.o

Id  | Name                    | 1st arg | 2sd arg | 3rd arg | return | input                       | output                   |
----|-------------------------|---------|---------|---------|--------|-----------------------------|--------------------------|
001 | upperCase               | string  | .       | .       | string | "Make this upper case"      | "MAKE THIS UPPER CASE"   |      
002 | lowerCase               | string  | .       | .       | string | "Make THIS loWer case"      | "make this lower case"   |
003 | camelCase               | string  | .       | .       | string | "Make this caMel Case"      | "makeThisCamelCase"      |
004 | pascalCase              | string  | .       | .       | string | "make this pascal CASE"     | "MakeThisPascalCase"     |
005 | snakeCase               | string  | .       | .       | string | "make this snake case"      | "make_this_snake_case"   |
006 | kebabCase               | string  | .       | .       | string | "make this kebab case"      | "make-this-kebab-case"   |
007 | reverseCase             | string  | .       | .       | string | "make this reverse case"    | "esac esrever siht ekam" |         
008 | leftTrim                | string  | .       | .       | string | "    remove left spaces"    | "remove left spaces"     |
009 | rightTrim               | string  | .       | .       | string | "remove right spaces   "    | "remove right spaces"    |
010 | trim                    | string  | .       | .       | string | "   remove extra spaces   " | "remove extra spaces"    |
011 | concat                  | string  | string  |         | string | "Join ", "us today!"        | "Join us today!"         |
012 | intToString             | int     | .       |         | string | 667                         | "667"                    |
013 | floatToString           | float   | .       |         | string | 667.677                     | "667.667"                |
014 | doubleToString          | double  | .       |         | string | 3.14159265359               | "3.1415"                 |

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Print.o library

@include Print.o

Id  | Name                    | 1st arg | 2sd arg | 3rd arg | return | input                       | output                   |
----|-------------------------|---------|---------|---------|--------|-----------------------------|--------------------------|
001 | print                   | string  | .       | .       | string | "print this string"         | "print this string"      |  
002 | print                   | integer | .       | .       | string | 2020                        | 2020                     |
003 | print                   | float   | .       | .       | string | 3.14f                       | 3.14                     |
004 | print                   | double  | .       | .       | string | 2.71828182845904d           | 2.718281828459045        |
005 | println                 | string  | .       | .       | string | "print this string"         | "print this string"      |  
006 | println                 | integer | .       | .       | string | 2020                        | 2020                     |
007 | println                 | float   | .       | .       | string | 3.14f                       | 3.14                     |
008 | println                 | double  | .       | .       | string | 2.71828182845904d           | 2.718281828459045        |

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Geometry.o library

@include Geometry.o




