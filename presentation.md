---
  title: Atividade Git Básico
  theme: blood
  revealOptions:
    transition: slide
---

<img src='assets/git-logo.png' style='width: 30%'/>
### Atividade de Git Básico

Autor: **Andrew Ribeiro**

---

### Instruções

Entregar por email _andrew.ribeiro@etec.sp.gov.br_

Colocar no assunto **ATIVIDADE-14-03-2019-PAM** <span class='c-yellow'>\*</span>

Aceito até as 22h30

<small><span class='c-yellow'>\*</span> Se não colocar, não conseguirei filtrar.

---

#### Visão Geral

> A atividade consiste em criar e manter um repositório git para um projeto fictício chamado:
**NoBullying**.

----

> O projeto **NoBullying** será uma programa em Java que exibe **10 passos
para combater o Bullying e evitar uma tragédia como a de Raul Brasil**.

----

> _Para fins de contextualização: Dois ex-alunos (17 e 25) da escola Raul Brasil, Suzano, SP invadiram a escola
e mataram 10 pessoas a tiros e machadadas, depois, se suicidaram.
Muitos relatos diziam que os dois sofriam **Bullying** na escola e tinham a família desestruturada._

---

## Como desenvolver o exercício?

----

# 1º

Montar a estrutura do projeto, que consiste em:

_Via **CMD**, criar uma pasta chamada <span class='c-yellow'>**pam-nobullying**</span> na Área de Trabalho_.

----

# 2º

Criar uma classe Java chamada **<span class='c-yellow'>NoBullying.java</span>** dentro da pasta criada.

----

# 3º

Escrever o seguinte código no arquivo **<span class='c-yellow'>NoBullying.java</span>**:

~~~~
public class NoBullying {
  public static void main(String[] args){
    System.out.println('Programa NoBullying');
  }
}
~~~~

----

# 4º

Inicializar um repositório vazio na nossa pasta **<span class='c-yellow'>pam-nobullying</span>**.

----

# 5º

Fazer o primeiro commit no repositório, que consiste em:

Adicionar o arquivo **<span class='c-yellow'>NoBullying.java</span>** ao **Staging Area** ou **Índice**.

Commitar o arquivo recém adicionado ao repositório.

_<small>PS: Escreva a mensagem: "Primeiro Commit do Projeto NoBullying"</small>_

----

# 6º

Pra cada passo, adicionar um novo *println* no arquivo Java:

~~~~
System.out.println("Passo 1: bla bla bla");

System.out.println("Passo 2: ble ble ble");
~~~~

----

# 7º

Pra cada passo (Dos 10 passos), fazer um commit. No final, precisamos ter 11 commits ao total.

_1 do commit inicial e mais 10 dos passos_

----

# 8º

Testar o código executando o seguinte comando:

~~~~
javac NoBullying.java

java NoBullying
~~~~

<small>Deverá aparecer na tela, os 10 passos para combater o Bullying e evitar uma tragédia.</small>

----

# 9º

Criar um novo repositório no *Github* e dar o nome de <span class='c-yellow'>pam-nobullying</span>
e sincronizar com seu repositório local, pra isso, executar:

~~~~
git remote add origin URL
~~~~

_<small>PS: Onde esta **URL**, substituir pela **URL** do seu **repositório do github**.</small>_

----

# 10º

Fazer upload dos seus commits para o repositório remoto:

~~~~
git push origin master
~~~~

----

# 11º

Enviar o link do seu repositório para mim.

---

## Bom exercício!
