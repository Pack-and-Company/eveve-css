#Eveve Stylesheets

Custom stylesheets for Eveve online bookings pages.

Note: the html can't be changed, and we can only use CSS (no scripts).

### Recommended stylesheet setup:

#### CSS Reset
```
/* Eric Meyer's Reset CSS v2.0 - http://cssreset.com */
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{border:0;font-size:100%;font:inherit;vertical-align:baseline;margin:0;padding:0}article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block}body{line-height:1}ol,ul{list-style:none}blockquote,q{quotes:none}blockquote:before,blockquote:after,q:before,q:after{content:none}table{border-collapse:collapse;border-spacing:0}
```

#### Reset Form Elements
```
/* Resets form inputs */
select, input, textarea { margin: 0; padding: 0; border: none; }
```

#### Override Inline Styles
Styles set in the html. Override with !important.
```
/* Override inline styles */
table { margin-left: 0 !important; }
```

#### Hide Pointless Content
You probably want to hide these elements:
```
/* Hide some stuff */
fieldset hr, h3:not(.time), br, a:empty { display: none; }
```
