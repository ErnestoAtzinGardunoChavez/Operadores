# Operadores
Operadores if y when

package com.example.myapplication

fun main(){ //verifAge() //gradoEscolar() //GradoEscolar()

} fun verifAge(){ print ("Ingrese edad y precione enter(escribe solo el numero):") val age = readLine()?.toInt()

if(age==18){
    println("Ya eres mayor de edad¡")
}
if(age!! >18){
    println("Ya eres mayor de edad")
}
else if (age!! == 18){
    println("Acabas de cumplir la mayoria de edad")

}
else{
    println("Eres menor de edad")
}
