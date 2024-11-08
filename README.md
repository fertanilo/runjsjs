# runjsjs
Los ejercicios del proyecto 🐒
//1
{
//suma tres numeros
let num1 = 5
let num2 = 6
let num3 = 7
let resultado = num1+num2+num3
console.log(resultado)
}
//2
{
// despejar x en 5x+50=60
let mx = 5
let n1 = +50
let f = 60
let despejev = 5
let despejen1 = 50 //es negativa
let operacion = (f-despejen1)/mx
let resultado = operacion
console.log(resultado)
}
//3
{
//centimetro a pulgadas
let centimetros = 49
let pulgadas = centimetros/24.5
console.log(pulgadas)
}
//4
{
//promedio
let par1 = 9
let par2 = 7
let par3 = 10
let par4 = 9.5
let promedio = (par1+par2+par3+par4)/4
console.log(promedio)
}
//5
{
//cuadrado 243
let num = 243
let cuadrado = num*num
console.log(cuadrado)
}
//6
{// modelo de auto
let marca = "fertanilo"
let modelo = "2008"
let final = marca+modelo
console.log(final)
}
//7
{
//millas marinas y normales
let mts = 1852
let mm = mts/1852
let m = mts/1609
console.log(mm)
console.log(m)
}
//8
{
//cuadrado de numero
let num = 4
let cuadrado = num*num
console.log(cuadrado)
}
//9
{
//cambio de la tienda
let precio = 187
let dd = 500
let cambio = dd-precio
console.log(cambio)
}
//10
{
//perimetro y area de un rectangulo
let base = 5
let altura = 4
let perimetro = altura+altura+base+base
let area = altura*base
console.log(perimetro)
console.log(area)
}
//11
{
//area y volumen de cilindro
let r = 2
let h = 8
let pi = 3.1416
let v = pi*(r*r)*h
let a = 2*(pi)*r*h+(pi+pi)*(r*r)
console.log(v)
console.log(a)
}
//12
{
//perimetro y area de triangulo
let h = 4
let x = 3
let y = 3
let z = 3
let perimetro = x+y+z
let area = (h*x)/2
console.log(perimetro)
console.log(area)
}
//13 esta en pagina random
{
//multiplicación de tres numeros
let num1 = prompt("ingrese el numero")
let num2 = prompt("ingrese el numero")
let num3 = prompt("ingrese el numero")
let mlt = num1*num2*num3
console.log(mlt)
}
//14
{
//compra de un terreno
let cm = 1500
let m = 150000
let costo = m*cm
console.log(costo)
}
//15
{
//perimetro y area triangulo
let b = 12
let h = 9
let p = b*b
let a = (b*h)/2
console.log(p)
console.log(a)
}
//16
{
let an = 2009
let aa = 2024
let edad = aa-an
console.log(edad)
}
//17 esta en pagina random
{
//promedio
let promedio = prompt("pon tu promedio")
if(promedio<7){
console.log("aprobaste")
}else{
  console.log("reprobaste")
}
  
}
//18 esta en pagina random
{
//numero=cero
let num = promt("ingresa un numero")
if(num=0){
console.log("es cero")
}else{
  console.log("no es cero")
}
}
//19 esta en pagina random
{
//suma positiva o negativa
let num1 = prompt("ingrese el numero")
let num2 = prompt("ingrese el numero")
let suma = num1+num2
console.log(suma)
}
//20 
{
//costo terreno 2.0
let com = 750
let area = 900
if (area> 500 ){
  console.log("tienes un descuento de 10%")
  let preciod = (com*area)/10*9
  console.log(preciod)
}else {
  console.log("el precio es normal")
  let precio = com*area
  console.log(precio)
}
//21 esta en pagina random
{
//exento
let cal1 = prompt("infresa tu calificacion")
let cal2 = prompt("infresa tu calificacion")
let cal3 = prompt("infresa tu calificacion")
let promedio = (cal1+cal2+cal3)/3
if(promedio>= 9){
 console.log("estas exento")
}else{
  console.log("reprobaste")
}
}
//22 esta en pagina random
{
//promedio final
let cal1 = prompt("infresa tu calificacion")
let cal2 = prompt("infresa tu calificacion")
let cal3 = prompt("infresa tu calificacion")
let promedio = (cal1+cal2+cal3)/3
if(promedio>= 9){
 console.log("estas exento")
}else if (promedio>6<9){
  console.log("eres ordinario")
}else{
  console.log("reprobaste")
}
}
//23 esta en pagina random
{
//numero positivo, negativo o cero
let num = promt("dame un numero")
if(num<0){
  console.log("es positivo")
}else if(num=0){
  console.log("es cero")
}else{
  console.log("es negativo")
}
}
//24 esta en pagina random
{
//dias deacuerdo a un numero
let dia = prompt("ingresa un numero del 1 al 7")
if(dia=1){
  console.log("lunes")
}else if(dia=2){
  console.log("martes")
}else if(dia=3){
  console.log("miercoles")
}else if(dia=4){
  console.log("jueves")
}else if(dia=5){
  console.log("viernes")
}else if(dia=6){
  console.log("sabado")
}else if(dia=7){
  console.log("domingo")
}else{
  console.log("Error de opción")
}
}
//25 esta en pagina random
{
//producto o suma dependiendo el signo
let num1 = prompt("ingresa el primer numero")
let num2 = prompt("ingresa el segundo numero")
let num3 = prompt("ingresa el tercer numero")
if(num1>-1){
  let suma = num1+num2+num3
  console.log(suma)
}else{
  let mult = num1*num2*num3
  console.log(mult)
}
}
//26 esta en pagina random
{
//aprobado o reprobado
let num1 = prompt("ingrese la calificación")
let num2 = prompt("ingrese la calificación")
let num3 = prompt("ingrese la calificación")
let num4 = prompt("ingrese la calificación")
let num5 = prompt("ingrese la calificación")
let promedio = (num1*num2*num3*num4*num5)/5
if(promedio>=6){
  console.log("aprobaste")
}else{
  console.log("reprobaste")
}
}
//27 esta en pagina random
{
//¿Qué triangulo es?
let l1 = prompt("ingresa el primer lado")
let l2 = prompt("ingresa el segundo lado")
let l3 = prompt("ingresa el tercer lado")
if(l1=l2 &&=l3){
  console.log("es un triangulo equilatero")
}else if(l1=l2, l1=l3){
  console.log("es un triangulo isosceles")
}else{
  console.log("es un triangulo escaleno")
}
}
//28 esta en pagina random
{
//numeros ordenados de mayor a menor
let num1 = prompt("dame un numero")
let num2 = prompt("dame un numero")
let num3 = prompt("dame un numero")
if(num1<num2 &&num2<num3){
  console.log(`${num3},${num2},${num1}`)
}else if(num1>num2 &&num2>num3){
  console.log(`${num1},${num2},${num3}`)
}else if(num1<num2 &&num2>num3){
  console.log(`${num2},${num1},${num3}`)
}else if(num1>num2 &&num2<num3){
  console.log(`${num1},${num3},${num2},`)
}else{
  console.log("no existe")
}
}
//29
{
//mes segun el numero
let mes = prompt("ingresa un numero del 1 al 12")
if(mes=1){
  console.log("enero")
}else if(mes=2){
  console.log("febrero")
}else if(mes=3){
  console.log("marzo")
}else if(mes=4){
  console.log("abril")
}else if(mes=5){
  console.log("mayo")
}else if(mes=6){
  console.log("junio")
}else if(mes=7){
  console.log("julio")
}else if(mes=8){
  console.log("agosto")
}else if(mes=9){
  console.log("septiembre")
}else if(mes=10){
  console.log("octubre")
}else if(mes=11){
  console.log("noviembre")
}else if(mes=12){
  console.log("diciembre")
}else{
  console.log("Error de opción")
}
}
//30
{
//ecuación de segundo grado
let num1 = 1
let num2 = 1
let num3 = -1
let x =(-num2+((num2*num2)-4*(num1*num3)/1))/num1*2
}
