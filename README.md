# Natural ou Fake Natty? Como Vencer na Era das IAs Generativas


DESCRIÇÃO DO PROJETO 🚀

Este projeto é incrível! 😄

______________________________________________________________________________________________________________________________________________________________________________________________

- O projeto irá demonstrar como uma tecnologia generativa específica pode facilitar a vida dos seres humanos em diversas questões
_____________________________________________________________________________________________________________________________________________________________________________________________
TECNOLOGIAS UTILIZADAS
_____________________________________________________________________________________________________________________________________________________________________________________________
- A tecnologia utilizada para esse projeto será o ChatGpt, onde solicitarei a ele respostas especifícas a cerca da própria tecnologia e um breve resumo sobre a técnica Machine Learning

  PROCESSO DE CRIAÇÃO 🖨️
_____________________________________________________________________________________________________________________________________________________________________________________________

- Solicitei ao ChatGPT que me informasse quais são os principais códigos utilizador na liguaguem de programação Kotlin .
- Pedi ao ChatGPT que fizesse para mim um resumo sobre o conceito e a utilização da técnica Machine Learning .

___________________________________________________________________________________________________________________________________________________________________________________________

RESULTADOS 

1- Claro! Aqui estão alguns dos principais conceitos e códigos usados na linguagem de programação Kotlin:

### 1. **Declaração de Variáveis**

Kotlin possui dois tipos de declaração de variáveis:

- **Mutable (variável que pode ser alterada)**:
  ```kotlin
  var nome: String = "João"
  nome = "Maria"
  ```

- **Immutable (variável que não pode ser alterada)**:
  ```kotlin
  val idade: Int = 25
  ```

### 2. **Funções**

Declaração de funções:
```kotlin
fun somar(a: Int, b: Int): Int {
    return a + b
}

// Chamada da função
val resultado = somar(5, 10)
```

### 3. **Classes e Objetos**

Definindo uma classe:
```kotlin
class Pessoa(val nome: String, var idade: Int) {
    fun apresentar() {
        println("Olá, meu nome é $nome e eu tenho $idade anos.")
    }
}

// Criando um objeto
val pessoa = Pessoa("João", 30)
pessoa.apresentar()
```

### 4. **Controle de Fluxo**

- **If-Else**:
  ```kotlin
  val numero = 10
  if (numero > 0) {
      println("Número positivo")
  } else {
      println("Número negativo ou zero")
  }
  ```

- **When** (similar ao switch):
  ```kotlin
  when (numero) {
      1 -> println("Um")
      2 -> println("Dois")
      else -> println("Outro número")
  }
  ```

### 5. **Listas e Coleções**

- **Listas**:
  ```kotlin
  val lista = listOf("Maçã", "Banana", "Laranja")
  for (fruta in lista) {
      println(fruta)
  }
  ```

- **Mutable List**:
  ```kotlin
  val listaMutavel = mutableListOf("Maçã", "Banana")
  listaMutavel.add("Laranja")
  ```

### 6. **Null Safety**

Kotlin tem um sistema de segurança de nulidade que ajuda a evitar NullPointerExceptions:

- **Variáveis não nulas**:
  ```kotlin
  var nome: String = "João" // Não pode ser nulo
  ```

- **Variáveis que podem ser nulas**:
  ```kotlin
  var nomeNullable: String? = null // Pode ser nulo
  ```

- **Operador Elvis**:
  ```kotlin
  val comprimento = nomeNullable?.length ?: 0
  ```

### 7. **Lambda e Funções de Ordem Superior**

- **Funções Lambda**:
  ```kotlin
  val soma = { a: Int, b: Int -> a + b }
  println(soma(5, 10))
  ```

- **Funções de Ordem Superior**:
  ```kotlin
  fun executarOperacao(a: Int, b: Int, operacao: (Int, Int) -> Int): Int {
      return operacao(a, b)
  }
  
  val resultado = executarOperacao(5, 10, soma)
  ```

### 8. **Tratamento de Exceções**

Kotlin também permite o tratamento de exceções com `try-catch`:
```kotlin
try {
    val resultado = 10 / 0
} catch (e: ArithmeticException) {
    println("Erro: ${e.message}")
}
```

2 - Claro! Machine Learning, ou aprendizado de máquina, é uma subárea da inteligência artificial que permite que sistemas aprendam e melhorem a partir de dados, sem serem explicitamente programados para cada tarefa.

**Funcionalidade:**

1. **Aprendizado a partir de dados:** O sistema analisa grandes volumes de dados e identifica padrões ou características relevantes.
   
2. **Modelagem:** Cria modelos matemáticos que podem prever resultados ou tomar decisões com base em novos dados.

3. **Aprimoramento contínuo:** À medida que mais dados são disponibilizados, o modelo pode ser ajustado para melhorar sua precisão.

4. **Aplicações diversas:** É usado em várias áreas, como reconhecimento de voz, recomendação de produtos, diagnósticos médicos, entre outros.

Em resumo, o Machine Learning permite que as máquinas aprendam com experiências passadas e tomem decisões de forma autônoma.
__________________________________________________________________________________________________________________________________________________________________________________________




