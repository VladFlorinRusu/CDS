---
  title: This is the title
  author: D. Author
  date: 14-02-2013
...
### 4.3

 Section 1
============

Subsection 
-----------

Section 2
===========

### 4.4

# Section 1

## Subsection 

### Subsubsection


### 4.5.

# Section 1
> This is a block quotation.  Block quotations are specified by
> proceeding each line with a > character.  The quotation block
> will be indented.
>
> To have paragraphs in block quotations, separate paragraphs
> with a line containing only the block quotation mark character.

  

### 4.6
# Section 1
  a = rnorm(10,5,2)
  for (i in 1:10) {
    print(a[1])
  }

### 4.7

 a = rnorm(10,5,2)
  for (i in 1:10) {
  print(a[1])
  }

# 5- Liste
# Section 1
  * This is the first bullet item
  * This is the second.  
    To indent this sentence on the next line,
    the previous line ended in two spaces and
    this sentence is indented by four spaces.
  * This is the third item


### 5.2

 # Section 1
  1. This is the first numbered item.
  2. This is the second.
  1. This is the third item.  Note that the number I supplied is ignored
  
  # Section 2
  (i) This is list with roman numeral enumerators
  (ii) Another item


### 5.3
# Section 1
Term 1
  :  This is the definition of this term
This is a phrase
  :  This is the definition of the phrase



### 5.4
  # Section 1
1. This is the first numbered item.
2. This is the second.
            i) this is a sub-point
            ii) and another sub-point
1. This is the third item.  Note that the number I supplied is ignored



### 5.5
# Section 1
  1. This is the first numbered item.
  2. This is the second.
  1. This is the third item.  Note that the number I supplied is ignored
  
<:!-- -->
  
  1. Another list.
  2. With more points


### 6
 # Section 1
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
  Praesent a velit quis ante dignissim dignissim eget vitae tellus. 
  Duis eget neque tellus, eu elementum leo. Nullam quis velit 
  in magna bibendum dictum. Curabitur tincidunt cursus tellus, 
  in egestas augue porta ut. 
  
  * * * *
  
  Phasellus facilisis porttitor elit, vel pretium felis volutpat in. 
  Praesent euismod sagittis tortor, eget varius nisi consequat eget. 
  Sed facilisis aliquet accumsan. Maecenas aliquam, dolor id hendrerit viverra, 
  lacus tortor elementum nunc, quis commodo ligula orci vel augue. Suspendisse 
  dolor purus, volutpat vel viverra vitae, laoreet blandit nulla.
  
  ---------
  
  In eros ligula, scelerisque id tempus nec, pulvinar vitae felis. Morbi
  tempor viverra orci, quis elementum metus lobortis sed. Curabitur sit amet ante massa.


### 7 Tabele
## 7.1
# Section 1
  Column A    Column B    Column C
  ---------  ----------  ---------
  Category 1    High        100.00
  Category 2    High         80.50
  ---------  ----------  ---------


### 7.2  
# Section 1
  --------------------------------
  Column A    Column B      Column 
                                 C
  ---------  ----------  ---------
  Category 1    High        100.00
  High         95.00
  
  Category 2    High         80.50
  High         82.50
  --------------------------------

### 7.3 Grid Tables

# Section 1
  +---------------+---------------+--------------------+
  | Fruit         | Price         | Advantages         |
  +===============+===============+====================+
  | Bananas       | $1.34         | - built-in wrapper |
  |               |               | - bright color     |
  +---------------+---------------+--------------------+
  | Oranges       | $2.10         | - cures scurvy     |
  |               |               | - tasty            |
  +---------------+---------------+--------------------+

  +-----------+----------+-----------+
  |Column A   |Column B  |   Column C|
  +===========+==========+===========+
  |Category 1 |100.00    | - point A |
  |           |          | - point B |
  +-----------+----------+-----------+
  |Category 2 | 85.00    | - point C |
  |           |          | - point D |
  +-----------+----------+-----------+


  ### 7.4 Pipe tables
   # Section 1
  | Default | left  | Center | Right  |
  |---------|:------|:------:|-------:|
  |   High  | Cat 1 | A      | 100.00 |
  |   High  | Cat 2 | B      |  85.50 |
  |   Low   | Cat 3 | C      |  80.00 |



  ### 8 Math
  # Section 1
The formula, $y=mx+c$, is displayed inline. 
Some symbols and equations (such as 
$\sum{x}$$ or $\frac{1}{2}$) are rescaled 
to prevent disruptions to the regular 
line spacing.
For more voluminous equations (such as 
$\sum{\frac{(\mu - \bar{x})^2}{n-1}}$), 
some line spacing disruptions are unavoidable.  
Math should then be displayed in displayed mode.
$$\\sum{\frac{(\mu - \bar{x})^2}{n-1}}$$


  ### 9 Referencing

  # Introduction
Bla Bla Bla

# Section 2
See the [introduction](#Introduction).




# Introduction
  Bla Bla Bla
  
  Table: this is the table caption [cap]: #cap
  
  | Default | left  | Center | Right  |
  |---------|:------|:------:|-------:|
  |   High  | Cat 1 | A      | 100.00 |
  |   High  | Cat 2 | B      |  85.50 |
  |   Low   | Cat 3 | C      |  80.00 |
  
  # Section 2
  See the [cap].


  ### 9.2 external links
  Goto the [Google search engine](http://www.google.com)