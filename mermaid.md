```mermaid
flowchart LR
    A-->B[test<a href='/test.md'>link</a>]
    B-->C
    C-->D
    click A callback "Tooltip for a callback"
    click B "https://github.com/JackyMO/sample/blob/master/test.md" _blank
    click C call callback() "Tooltip for a callback"
    click D href "test.md" _blank
```
