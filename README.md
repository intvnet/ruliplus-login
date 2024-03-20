# Sign in with 2game

### ※ Getting Start
```
<script src="https://ruliplus.com/2game/39r9orufeh/sign.js"></script>
```
<br><br>
### ※ ID info requset Method
**ruliplus_sign.get_member_info()**<br>
*JS Window.postMessage() use ID info Data send*
#### **req URL (only)**
**https://2game.com<br>**
or<br>
**https://www.2game.com**
<br><br>

### ※ How to receive Data
*JS addEventListener() use data recive  
(eventType = message)*
<br><br>
### ※ response JSON data
|parameter|type||
|---|---|---|
|result|Int|status code <br>*200* : success <br> *401* : Unauthorized|
|response|Array| *mb_id(str)* : user id(ruliplus) <br> *mb_name(str)* : user name <br> *mb_email(str)* : user e-mail address <br> *mb_hp(str)* : user cellphone number ex.010-1234-1234 <br> *mb_zip(str)* : user address zip code <br> *mb_addr1(str)* : user Street Address <br> *mb_addr2(str)* : user 2nd Address line <br> |

<br><br>
### ※ Example code (sample.html)
