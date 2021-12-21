# Vadzim Antonau

## Contacts

- **Location**: Minsk, Belarus
- **Email**: vanet@tut.by
- **Telegram**: @thorsangervanet
- **Discord**: @VaNeT#5916
- **[LinkedIn](https://www.linkedin.com/in/vadzim-antonau-394358119/)**

## About Me

I have studied programming since primary school (Basic, Pascal, Delphi). I got my first job as a Software Engineer after my graduation in 2011. I have developed and supported some Lotus Notes applications in my first year. I have become web developer after that. I didn't finish any courses I learned all by myself. We have used PHP for backend and HTML, CSS, jQuery for frontend at the begining.

## Skills

- PHP, Yii2
- HTML, CSS
- JavaScript, Node.js, Typescript
- jQuery, Bootstrap
- MySQL, MS SQL, FireBird, Oracle basics
- Git, Mercurial
- NetBeans, VS Code
- XML, XSLT, ISOSTS XML Scheme
- SOAP, REST API, JWT
- Ubuntu basics, bash-scripting
- Docker basics, Python basics, React.js basics
- Microsoft Office, VBA
- Adobe Photoshop, Adobe Acrobat, Pitstop Pro

## Code Example

[Isograms KATA from CODEWARS](https://www.codewars.com/kata/54ba84be607a92aa900000f1): An isogram is a word that has no repeating letters, consecutive or non-consecutive. Implement a function that determines whether a string that contains only letters is an isogram. Assume the empty string is an isogram. Ignore letter case.

```
function isIsogram(str){
  return str == '' || !str.toLowerCase().split('').some(function(v,i,a){
    return a.lastIndexOf(v)!=i;
  });
}
```
