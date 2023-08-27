function palindrome(str) {
    console.log(str);
    var re = /[^a-z0-9]/gi;
    var strString = str.toString();
    console.log(strString);
    var lowRegStr = strString.toLowerCase();
    console.log(lowRegStr);
    var strReplaced = lowRegStr.replace(re, '');
    console.log(strReplaced); 
    var reverseStr = strReplaced.split('').reverse().join('');
    console.log(reverseStr); 
     if (reverseStr === strReplaced){
       return true;
     } 
    else return false;
}



//const replacedStr = str.replace(/[^a-z0-9]/gi, '');
//console.log(replacedStr);
//or
//str.replace();
//console.log(str.toLowerCase()); 

palindrome("eye");
