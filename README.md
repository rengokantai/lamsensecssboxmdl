### lamsensecssboxmdl
####
#####Changing the contents within the box
#####Position is everything
relative:following element will not fill  
absolute:following element will fill
[demo](https://jsfiddle.net/rengokantai/5041rqnL/)
#####Floating and clearing content

#####Pseudo-elements: Making the browser hallucinate
class: alter the display or behavior of all the contents inside an element box  
elements: alter the display or behavior of a certain part the contents inside an element box   
before, after,first-letter,first-line,selection.,backdrop  

#####Creating flexible boxes with display: Flex
basic centering
```
.wrapper{
  display: flex;
  align-items:center;
  justify-content:center;
}
```
#####Changing the shape outside
```
.wrapper{
-webkit-shape-outside:circle();
}
```
others
```
-webkit-clip-path
```
