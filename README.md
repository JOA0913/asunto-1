# recursividad

La recursividad es una técnica muy empleada en programación que consiste en la capacidad de una función de llamarse a sí misma. Es decir, una función recursiva está definida en función de sí misma, y se llamará a sí misma hasta que se cumpla una condición1. La recursividad es un principio o técnica que implica que una función, proceso o estructura se repite a sí misma en una forma similar o idéntica![ft recu](https://github.com/user-attachments/assets/1582be09-9990-40a0-81ce-f179bc960082)
`fun mostrarDel5Al1(n: Int) {
    if (n < 1) return  // Caso base: si n es menor que 1, termina la recursión
    println(n)         // Imprime el número actual
    mostrarDel5Al1(n - 1) // Llama a la función con el número decrementado
}

fun main() {
    mostrarDel5Al1(5) // Inicia la recursión desde 5
}
