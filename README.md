#### psmakwebformaccess
#####using wai-aria
######what
ARIA is just for exposing info to sscreen readers,it doesnot influence browser behaviour
######lebaling
```
<input type="text" aria-label="name"/>  //label text for the control
<input type="text" aria-labelledby="name"/>  //control is labelled by another control
```
aria-label
```
<input type="text" aria-label="Search Term"/>  //portable reader will read this
```
aria-describedby   //refer a id
```
<input type="text" aria-describedby="n"/> 
<p id="n">will read this</p>
```
######live updating
aria-live  // polite,assertive  

aria-atomic="true"  //false means only the elements that changed,true means all the child elements  

aria-busy="true" //force the screen reader to wait

#####adding some final
check wcag:
```
wave.webaim.org
```
ahother tool
```
tenon.io: minimun wcag level=AA
```
