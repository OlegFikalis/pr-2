![задание](https://user-images.githubusercontent.com/70691206/97531602-9260c800-19c5-11eb-8de7-b9bc0249a6cb.jpg)  

Мне было лень читать теорию, поэтому попытаюсь логически (и немного гугля (ну и подсматривая в другие практические)) что-то понять  
Пятым же пакетом был обнаружен ICMP-голубчик, но я не нашел данных о размере пакета (может я даун)  
*Мой IP написан у меня на груди (нашел через __https://2ip.ru/__)*  
![](https://user-images.githubusercontent.com/70691206/97538784-0903c280-19d2-11eb-90c1-f1ddfd718bd0.jpg)  
   
   
__*Я решил пойти другим путем и обменялся пактеами (кажется) с гуглом (не помню)__ 
![](https://user-images.githubusercontent.com/70691206/97539734-8aa82000-19d3-11eb-923b-a0ced7d79672.jpg)  
    
__Об полученном пакете можно узнать (из того, что я смог разобрать) следующее:__  
![1](https://user-images.githubusercontent.com/70691206/97542482-da88e600-19d7-11eb-97fd-7941b37e81df.jpg)
 
__Время жизни пакета__  
![1](https://user-images.githubusercontent.com/70691206/97554171-75d58780-19e7-11eb-995c-ff4f3ba420c4.jpg)  
   
__В заголовке содержится 20 байт, общая длина 60 байт__  
![1](https://user-images.githubusercontent.com/70691206/97547385-cc8a9380-19de-11eb-9356-2a187a8ab019.jpg)
 
__Тип: Echo-запрос, доп. информация не нужна__  
![](https://user-images.githubusercontent.com/70691206/97542009-1a9b9900-19d7-11eb-9a1f-868d622a0320.jpg)
 
__Вот цифровое представление (так пакет летает по сети)__  
![](https://user-images.githubusercontent.com/70691206/97541384-2175dc00-19d6-11eb-8cfd-011f2bc32d7b.jpg)
 

 

 

 

 
![задание](https://user-images.githubusercontent.com/70691206/97556785-f649b780-19ea-11eb-9436-6534e90b89bf.jpg)
   
Взял для примера сайт _http://vansamaofficial.com/_  
1) **nslookup**  
![](https://user-images.githubusercontent.com/70691206/97573483-e4701080-19fa-11eb-8ff2-c80b3f8ec2ba.jpg)  
2) **ping**  
![](https://user-images.githubusercontent.com/70691206/97573206-74618a80-19fa-11eb-95d3-5a89a655db18.jpg)  
3) **tracert**
