# Dom Manipulation Assignment Answer
## Answer-1
### code
```javascript
//for name
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2 " ).innerText="Prajwal Rajendra zingare "
//for description
document.querySelector(".side-bar .crayons-card p" ).innerText="I am FullStack Javascript Developer and Satvic LifeStyle Follower"
 ```
### output

![Output](./image/ssc1.png)

## Answer-2
### code
```javascript

 ```
 ### output
 
![Output](./image/ssc2.png)
 
## Answer-3
### code
```javascript
const section = document.createElement("section")
section.classList.add("parent")
const newItem=document.querySelector(".accordion-homepage")
const h3=document.createElement("h3");
const textNode = document.createTextNode("My New FAQ");
h3.appendChild(textNode);
newItem.appendChild(section);
section.appendChild(h3);

 ```
 ### output

![Output](./image/ssc3.png)
 
## Answer-4
### code
```javascript
document.querySelector(".contact-us .customer-support a").innerText="+91 1213141516"

 ```
 ### output

![Output](./image/ssc4.png)

## Answer-5
### code
```javascript
document.querySelector(".diwali-deals-product-sale-btn").innerText="Check Out";

 ```
 ### output

![Output](./image/ssc5.png)

## Answer-6
### code
```javascript
document.querySelector(".searchinput___zXLAR").addEventListener("mouseover", function() {
    document.querySelector(".searchinput___zXLAR").style.backgroundColor = "red";
});

 ```
 ### output

![Output](./image/ssc6.png)

## Answer-7
### code
```javascript
function search(Text) {
  let input = document.querySelector("#hp-search-input");
  input.value = Text;
  let form = document.querySelector("#hp-search-form");
  form.submit();
}
search("css");

 ```
 ### output

![Output](./image/ssc7.png)

## Answer-8
### code
```javascript
let arr = document.querySelectorAll("#SIvCob a");
for (i = 0; i < arr.length; i++) {
  if (i % 2 != 0) {
    arr[i].remove();
  }
}
console.log(arr);

 ```
 ### output

![Output](./image/ssc8.png)

## Answer-9
### code
```javascript
document.querySelector(".display-heading-1").style.fontFamily="monospace";
document.querySelector(".display-heading-1").style.color="#b1361e";

 ```
 ### output

![Output](./image/ssc9.png)

## Answer-10
### code
```javascript
document.querySelector(".btn-cta-big .login-btn-text ").addEventListener("mouseover",function(){
    
      document.querySelector(".btn-cta-big .login-btn-text ").style.backgroundColor="red"
    
});

 ```
 ### output

![Output](./image/ssc10.png)

## Answer-11
### code
```javascript
document.querySelector(".gtag .icon").style.backgroundImage="url('https://ineuron.ai/images/ineuron-logo.png')"

 ```
 ### output

![Output](./image/ssc11.png)

## Answer-12
### code
```javascript
document.querySelector(".btn-primary").style.backgroundColor="blue"

 ```
 ### output

![Output](./image/ssc12.png)
## Answer-13
### code
```javascript
   document.querySelector(".fl-heading ").innerText="JS Bootcamp"

 ```
 ### output

![Output](./image/ssc13.png)

## Answer-14
### code
```javascript
  document.querySelector(".HotDealsAll__Heading__2fIbe").style.fontSize="80px"

 ```
 ### output

![Output](./image/ssc14.png)

## Answer-15
### code
```javascript
 document.querySelector(".ps-title").style.textAlign="right"

 ```
 ### output

![Output](./image/ssc15.png)

## Answer-16
### code
```javascript
document.querySelector(".section-title_title__VEDfK").innerText="Start with scrarch"

 ```
 ### output

![Output](./image/ssc16.png)

## Answer-17
### code
```javascript
document.querySelector(".btn-container").innerHTML=new Date()

 ```
 ### output

![Output](./image/ssc17.png)

## Answer-18
### code
```javascript
document.querySelector(".p-f03-footer-container .p-footer").style.backgroundColor="orange"

 ```
 ### output

![Output](./image/ssc18.png)

## Answer-19
### code
```javascript
document.querySelector(".navbar-brand .logo").src

 ```
 ### output

![Output](./image/ssc19.png)

## Answer-20
### code
```javascript
document.querySelector(".wide .desc").style.color="orange"

 ```
 ### output

![Output](./image/ssc20.png)

