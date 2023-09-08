# latex-template-ACM-IEEE
A Latex template that can easily switched between ACM and IEEE documents

Switching between ACM format and IEEE format is simple by comment out the line that defines that value for ```acmflag``` in ```main.tex```.
For example, the document is set to ACM format if the third and fourth lines are as follows:
```
%\togglefalse{acmflag}
\toggletrue{acmflag}
```
For another example, the document is set to IEEE format if the third and fourth lines are as follows:
```
\togglefalse{acmflag}
%\toggletrue{acmflag}
```
