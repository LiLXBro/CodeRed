**Cascading Algorithm**
1) Position- Position of the selector, the selector which is style at last would be used.
2) Specificity- Algorithm that determines which algorithm has strongest match.
    **!important>inline selector(1000)>id slector(100)>class/attribute selector(10)>element selector(1)>universal selector(0)**
3) origin: whether the style is allotted by developer or browser by default.
            **developer>browser style**
4) important: any style which flagged important would be applied first.
                **eg code- div{
                    color:blue !important;
                }**