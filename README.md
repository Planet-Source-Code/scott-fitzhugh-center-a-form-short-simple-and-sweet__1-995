<div align="center">

## Center a form \- Short, Simple, and Sweet


</div>

### Description

This code allows you to quickly center a form within the screen without eating up alot of cpu time.
 
### More Info
 
none. The form gets centered.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Scott Fitzhugh](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/scott-fitzhugh.md)
**Level**          |Unknown
**User Rating**    |3.3 (10 globes from 3 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/scott-fitzhugh-center-a-form-short-simple-and-sweet__1-995/archive/master.zip)





### Source Code

```
sub form_load()
me.left = (screen.width / 2) - (me.width / 2)
me.top = (screen.height / 2) - (me.height / 2)
end sub
```

