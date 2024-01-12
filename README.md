# 5-lab
<p></p>

<h2 align="center">ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ПРОФЕССИОНАЛЬНОГО ОБРАЗОВАНИЯ <br> «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ» <br> КАФЕДРА ИНФОРМАТИКИ </h2>
<p align="center">Лабораторная работа №5 <br>
по предмету «Web-технологии, языки и средства создания web-приложений» 

<p align="center"><b>"Java Script"</b><p>
<p align="right"><b>Выполнил: </b> студент 331 группы Хорошко Илья Алексеевич</p>
<p  align="right"><b>Проверил: </b> Соболев Е. И., старший преподователь</p>
<br>
<br>
<br>
<p align="center">Южно-Сахалинск <br> СахГУ <br> 2023</p>
<h2> Введение </h2>
<p>Лабораторные работы по дисциплине «Web-технологии, языки и средства создания web-приложений» предназначены для освоения полученных теоретических знаний на практике. <br>
	<p>Цели:</p>
<ol>
  <li>Овладеть навыками работы с языком гипертекстовой разметки HTML, в частности научиться основам Java Script, создавать простые скрипты для решения задач.
</ol>
В соответствии с данными целями необходимо решить следующие задачи:
<ol>
   <li> Написать скрипты для решения данных задач.
   </ol>

</p>
<h2>Решение задач</h2>
<p> 23  задачи: </p>
<code>

    <script>
    //№1
    document.write("Задание 1");
    document.write("<br>");
     let str='hdfgv';
     document.write(str[0]+','+str[1]+','+str[4]);
    
    //№2
    document.write("<br>");
    document.write("Задание 2");
    let secondHous=60*60;
    document.write('в часу '+secondHous+ ' секунд');
    
        //№3
    document.write("<br>");
    document.write("Задание 3");
    document.write("<br>");
     var num=1;
     num+=12;
     num-=14;
     num*=5;
     num/=7;
     num++;
     num--;
     alert(num);
 
    
    //№4
    var num=3;
    alert(num);
    
    //№5
    document.write("<br>");
    document.write("Задание 5");
    document.write("<br>");
    document.write(a+b);
    document.write(a-b);
    document.write(a*b);
    document.write(a/b);
    //№6
    document.write("<br>");
    document.write("Задание 6");
    document.write("<br>");
    var c=15,d=2;
    var result=c+d;
    document.write(result);
    
    //№7
    document.write("<br>");
    document.write("Задание 7");
    document.write("<br>");
    var c=5, a=10, b=2;
    resut=c+a+b;
    document.write(resut);
    
    //№8
    document.write("<br>");
    document.write("Задание 8");
    document.write("<br>");
    var a=17, b=10;
    c=a+b;
    d=7;
    result=c+d;
    document.write(result);
    
    //№9
    document.write("<br>");
    document.write("Задание 9");
    document.write("<br>");
    let secondHous=60*60;
    let secondSut=secondHous*24;
    let secondManth=secondSut*31;
    document.write('в часу '+secondHous+ ' секунд'+' в сутках '+secondSut+ ' секунд'+' в месяце 
    '+secondManth+ ' секунд');
    
    //№10
    document.write("<br>");
    document.write("Задание 10");
    document.write("<br>");
    let hour=12;
    let minute=50;
    let second=37;
    document.write(hour+':'+minute+':'+second);
    
    //№11
    document.write("<br>");
    document.write("Задание 11");
    document.write("<br>");
    var a=17
    result=a*a;
    document.write(result);
    
    //№12
    document.write("<br>");
    document.write("Задание 12");
    document.write("<br>");
    document.write(  [1, 2, 3, 4, 5, 6, 7,8,9,10].filter(n => n % 2 == 0).reduce( (sum, n) => sum + n**0.5, 
    0 ));
    
    //№13
    document.write("<br>");
    document.write("Задание 13");
    document.write("<br>");
    var apple = 1.15, orange = 2.30
    result= apple + orange;
    document.write(result);
    
    //№14
    document.write("<br>");
    document.write("Задание 14");
    document.write("<br>");
    var x=5;
    alert(x++);
    
    //№15
    document.write("<br>");
    document.write("Задание 15");
    document.write("<br>");
    var result = []+false-null+true;
    document.write(result);
    
    //№16
    document.write("<br>");
    document.write("Задание 16");
    document.write("<br>");
    let y=1;
    let x=y=2;
    console.log(x);
    
    //№17
    document.write("<br>");
    document.write("Задание 17");
    document.write("<br>");
    var result = []+1+2;
    document.write(result);
    
    //№18
    document.write("<br>");
    document.write("Задание 18");
    document.write("<br>");
    a6=5%3;
    a7=3%5;
    a8=5+'3';
    a9='5'+3;
    a10=75+'kg'
    document.write(a6);
    document.write(a7);
    document.write(a8);
    document.write(a9);
    document.write(a10);

    
    //№19
    document.write("<br>");
    document.write("Задание 19");
    document.write("<br>");
    const heigth =23;
    const width =10;
    const s= heigth * width;
    document.write(s);
    
    //№20
    document.write("<br>");
    document.write("Задание 20");
    document.write("<br>");
    const heigthC =23;
    const dC =10;
    const v= Math.PI*Math.pow(dC/2,2)*heigthC;
    document.write(v);
    
    //№21
    document.write("<br>");
    document.write("Задание 21");
    document.write("<br>");
    let s = 2e6, p=10, years=5;
    let pereki = (s*(p/100)*years);
    document.write('сумма переплат '+ pereki +' руб');
    
    //№22
    document.write("<br>");
    document.write("Задание 22");
    document.write("<br>");
    let str="привет", num=123, flag=true, txt="true";
    document.write(typeof str =='string');//true
    document.write(typeof num =='number');//true
    document.write(typeof flag =='boolean');//true
    document.write(typeof txt =='string');//true
    
    //№23
    document.write("<br>");
    document.write("Задание 23");
    document.write("<br>");
    const num = 5;
    result = num*-1;
    document.write(result);
    </script>
</code>
<p>На второй странице  задачи с  codewars.com:</p>
<code>


Remove String Spaces
JavaScript:
function noSpace(x){
  return x.replace(/\s/g, '');
}


Count the number of cubes with paint on
JavaScript:
const countSquares = cuts =>
  cuts == 0 ? 1 : cuts == 1 ? 8 : (cuts + 1) ** 3 - (cuts - 1) ** 3
/*
0 = 1
1 = 8
2 = 26  =>  1
3 = 56  =>  8
4 = 98  => 27
5 = 152 => 64
*/


Find Nearest square number
JavaScript:
function nearestSq(n){
  if (n == 1) return n
    var z = Math.sqrt(n)
    var res = Math.round(z)
   var result = res*res
    return result
}



Simple multiplication
JavaScript:
function simpleMultiplication(number){
    return (number % 2 == 0)? number * 8 : number * 9;
}


Determine offspring sex based on genes XX and XY chromosomes
JavaScript:
function chromosomeCheck(sperm) {
if(sperm == "XY")
{
  return "Congratulations! You're going to have a son.";
}
return "Congratulations! You're going to have a daughter.";
}


Is your period late?
JavaScript:
function periodIsLate(last, today, cycleLength) {
			var temp = Math.ceil((today - last)/(1000*60*60*24));
			if (temp > cycleLength) return true; else return false;
  }
  <p>ссылка на мой профиль в codewars: https://www.codewars.com/users/LongWayyy/completed </p>
<h2>Вывод:</h2>
<p> При помощи таких средств как  HTML, CSS, получилось решить все задачи. </p>
