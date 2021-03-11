## ES 2015
1. Arrow function expressions
 * Arrow function có thể thay thế cho biểu thức hàm thông thường trong một số trường hợp  *
 <space> <space>
 ``` 
 const array = [
     1,
     2
 ];

 console.log( arrat.map( value => value *2 ) );

 // result [2, 4];
 ```
  <space> <space>
2. Enhanced object  literals
* Object literals được mở rộng để hỗ trợ thiết lập cấu trúc đối tượng * 
```
// old define object
var a = 1, b = 2, c = 3;
var obj = {
    a : a,
    b : b,
    c : c
};
// obj.a = 1, obj.b = 2, obj.c = 3
// new define in Es6

const a = 1, b = 2, c = 3 ;

var obj = {
    a,
    b, 
    c
}
// obj.a = 1, obj.b = 2, obj.c = 3
```
 <space> <space>
3. Classes 
* Chúng ta có thể tạo class(lớp) mới sử dụng từ khóa  **class**  *
```
class Profile {   
   constructor(surname, firstname= '') { // class constructor
      this.surname= surname;
      this.firstname= firstname;     
   }  
    
   getName() { // class method       
     console.log(`Full Name: ${this.surname} ${this.firstname}`);    
   } 
}
let obj = new Profile('patel', 'atit');
obj.getName(); // Full Name: patel atit
```
 <space> <space>
4. Template Literals 
* chúng ta có thể sử dụng biến trong chuỗi bằng cánh sử dụng `${variable}` *

```
const name = `Your name is ${surname} ${firstname}.`
```


