# 📚 Sistema de Controle de Alunos em C++

Projeto desenvolvido em linguagem C++ para cadastrar alunos de uma turma e calcular informações sobre aprovação, idade e desempenho e media

---

# 🚀 Funcionalidades

- Cadastro de alunos
- Cadastro de notas
- Cálculo da média dos alunos
- Verificação de aprovação/reprovação
- Média de idade da turma
- Quantidade de aprovados e reprovados
- Percentual de aprovação por sexo

---

# 🛠️ Tecnologias Utilizadas

- Linguagem C++
- Biblioteca `stdio.h`

---

# ▶️ Como Executar

## Compilar

```bash
gcc main.c -o sistema
```

## Executar

### Linux / Mac

```bash
./sistema
```

### Windows

```bash
sistema.exe
```

---

# 📋 Informações do Sistema

O programa solicita:

- Quantidade de alunos
- Quantidade de provas
- Média para aprovação
- Nome
- Idade
- Sexo
- Notas dos alunos

---

# 📌 Estrutura Utilizada

```c++
struct Aluno {
	char Nome[30];
	char Sexo;
	int Idade;
	float Notas[10];
	float Media;
	bool Aprovado;
};
```

---

# 📸 Exemplo de Uso

```text
Informe a quantidade de alunos da turma: 2
Informe quantas provas: 3
Informe a media de aprovacao? 6

Informe o nome do 1. aluno: Gabriel
Informe a idade de Gabriel: 20
Informe o sexo de Gabriel [M/F]: M
Informe a 1 nota: 7
Informe a 2 nota: 8
Informe a 3 nota: 9
```

---

# 📚 Conceitos Aplicados

- Structs
- Vetores
- Loops
- Condicionais
- Funções matemáticas
- Entrada e saída de dados

---

# 👨‍💻 Autor

Desenvolvido por G.Dickson 
