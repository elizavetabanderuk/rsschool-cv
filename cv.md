![Photo](assets/img/photo_cv.jpg "Elizaveta Banderuk") 
# Elizaveta Banderuk 
### Junior Frontend Developer 
*****  
## Contact information 
* Location: Minsk, Belarus    
* E-mail: e.banderuk@gmail.com  
* LinkedIn: [Elizaveta Banderuk](www.linkedin.com/in/liza-banderuk)  
* GitHub: [elizavetabanderuk](https://github.com/elizavetabanderuk)  
  
## Profile   
I've been an international affairs manager for 5 years, working with partners from America, Europe and Asia. I have C1 level in English and a lot of expertise in spoken and written communication.   
Now I am studying to become a frontend developer. I believe my business knowledge and experience will help me succeed in this job.   

## Skills  
1. HTML  
2. CSS 
3. JavaScript 
4. Git/GitHub 
5. Python  
 
## Code example   
```  
var fs = require('fs');

const path = require('path');

var myPath = path.join(__dirname,'secret-folder');

let rs = function() {
    return fs.promises.readdir(myPath).then(token => { return token } )
  }
  
  let userToken = rs();
  
  userToken.then(function(result) {
     console.log(result)
     for (let i = 0; i < result.length; i++) {
         let Path = path.join(__dirname,'secret-folder',result[i]);
        
     fs.stat(Path,(err,stats)=>{
         if (err) {
             return console.log(err);
         } else if (stats.isFile()) {
             let newResult = result[i].split(".");
            console.log(newResult[0] + ' - ' + newResult[1] + ' - ' + stats.size/1000 + 'kb');
         }
         
     })
  }
}) 
``` 
 
## Education 
**Belarusian State Economic University (2014-2019)** - Master of Economics *(International economic affairs management)*   
**Code Basics** - Python для начинающих  
**The Rolling Scopes** - JS/FE Pre-School 2022  
**Alison Course (March 2021)** - Agile Essentials: A Practical Guide to the Agile Process  
 
## Languages 
 
| Language    | Level of proficiency | Link to certificate                                     | 
|:---------   |:--------------------:|--------------------------------------------------------:| 
| English     | C1 ADVANCED          | [EF SET Certificate](https://www.efset.org/cert/T1JQRy) | 
| German      | A2 ELEMENTARY        | None                                                    | 
| Russian     | C2 PROFICIENT        | Native speaker                                          | 
 