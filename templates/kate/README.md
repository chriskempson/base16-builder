Kate Base16 syntax highlighting
===============================

## File format

The first number in the list relates to the default value for the type, defined in [include/ktexteditor/attribute.h](https://quickgit.kde.org/?p=ktexteditor.git&a=blob&h=7fb1941c2f6a2ce4287ed4620788eb7df6aa6aca&hb=fc025358eff33178cdb6670c1ddb223938c66517&f=src%2Finclude%2Fktexteditor%2Fattribute.h)


* > **Normal Text**

&ensp; 0.&nbsp; Normal  
  &emsp;&nbsp;&emsp;Default for normal text and source code.

1. Keyword  
  Used for language keywords.

1. Function  
  Used for function definitions and function calls.

1. Variable  
  Used for variables, if applicable.

1. ControlFlow  
  Used for control flow highlighting, e.g., if, then, else, return, continue.

1. Operator  
  Used for operators such as `+`, `-`, `*`, `/` and `::` etc.

1. BuiltIn  
  Used for built-in language classes and functions.

1. Extension  
  Used for extensions, such as Qt or boost.

1. Preprocessor  
  Used for preprocessor statements.

1. Attribute  
  Used for attributes of a function, e.g. `@override` in Java.

  > **Strings & Characters**

1. Char  
  Used for a single character.

1. SpecialChar  
  Used for an escaped character.

1. String  
  Used for strings.

1. VerbatimString  
  Used for verbatim strings such as HERE docs.

1. SpecialString  
  Used for special strings such as regular expressions or LaTeX math mode.

1. Import  
  Used for includes, imports and modules.

  > **Number, Types & Constants**

1. DataType  
  Used for data types such as int, char, float etc.

1. DecVal  
  Used for decimal values.

1. BaseN  
  Used for numbers with base other than 10.

1. Float  
  Used for floating point numbers.

1. Constant  
  Used for language constants.

  > **Comments & Documentation**

1. Comment  
  Used for normal comments.

1. Documentation  
  Used for comments that reflect API documentation.

1. Annotation  
  Used for annotations in comments, e.g. `@param` in Doxygen or JavaDoc.

1. CommentVar  
  Used to refer to variables in a comment, e.g. after `@param` in Doxygen or JavaDoc.

1. RegionMarker  
  Used for region markers, typically defined by BEGIN/END.

1. Information  
  Used for information, e.g. the keyword `@note` in Doxygen.

1. Warning  
  Used for warnings, e.g. the keyword `@warning` in Doxygen.

1. Alert  
  Used for comment specials TODO and WARNING in comments.

  > **Misc**

1. Others  
  Used for attributes that do not match any of the other default styles.

1. Error  
  Used to indicate wrong syntax.
