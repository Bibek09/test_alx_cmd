# test_alx_cmd
http://whatdidilearn.info/2018/07/08/implementing-hello-world-alexa-skill.html
https://developer.amazon.com/blogs/alexa/post/d8579cd6-9109-42b2-ada6-df017fc1dee5/how-to-handle-different-intent-requests-with-dialog-management
https://developer.amazon.com/blogs/alexa/post/5b0efd02-0ed0-42d5-b922-5ee594d30a38/new-alexa-skills-kit-template-build-an-alexa-decision-tree-skill
https://tutorials.botsfloor.com/how-to-build-a-hello-world-alexa-skill-bcea0d01ee8f

``` javascript
ask simulate -t "Alexa open hello world" -l en-US -s "amzn1.ask.skill.9bfdbdfb-406b-40a1-94" --profile default

# https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html
If you have multiple profiles, you can configure additional, named profiles by using the --profile option.
$ aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: us-west-2
Default output format [None]: json

```

https://www.webdesignerdepot.com/2011/07/40-useful-apis-for-web-designers-and-developers/
https://cloud.google.com/prediction/docs/developer-guide

 ```javascript

<script>
var a=5; b=9;
//calculate 2 numbers
window.alert(a+b);
window.alert(myFunction(a, b)) ;

//Array
var person = {firstName:"John", lastName:"Doe", age:46};
window.alert(person["firstName"]);

//Array single or double quote, all okay!
var hillstations = ['Kalimpong', "Pedong", "Algarah"];
window.alert(hillstations[0]);



function myFunction(p1, p2) {
var x = 'It\'s alright.';
if(x='It\'s alright.'){
window.alert("heee");
}

switch(x) {
    case 'It\'s alright.':
        window.alert("heee");
        break;
    case n:
        //code block
        break;
    default:
        //code block
}

var d = new Date();
window.alert(x +d);
    return p1 * p2;              // The function returns the product of p1 and p2

}

</script>
 ```
