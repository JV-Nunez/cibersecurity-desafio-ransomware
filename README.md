# Projeto Ransomware Simples em Python

### Descrição

Este projeto faz parte de um desafio promovido pela plataforma Digital Innovation One, em parceria com o Santander, que incentiva a elaboração criptografador e um descriptografador de arquivos simples, utilizando a linguagem Python. O objetivo é demonstrar o processo de criação de um ataque, de maneira simplificada, no Kali Linux.

### Ferramentas Utilizadas

- Kali Linux

### Estrutura do Projeto

O projeto é composto por três arquivos:

- encrypter.py: Script responsável por criptografar o arquivo teste.txt.
- decrypter.py: Script responsável por descriptografar o arquivo criptografado.
- teste.txt: Arquivo de exemplo utilizado para teste.

### Funcionamento

#### Criptografia

- Execução do script ```python encrypter.py```
  
_Esse comando abre o arquivo original, lê os dados contidos nele e o remove. Em seguida, criptografa os dados utilizando *pyaes* com uma chave fixa e salva os dados criptografados em um novo arquivo chamado teste.txt.criptografado._

#### Descriptografia

- Execução do script ```python decrypter.py```
- Inserção da senha (no exemplo: 1234)
  
_Esse comando abre o arquivo criptografado e descriptografa os dados utilizando a mesma chave fixa. Em seguida, remove o arquivo criptografado e cria um novo arquivo chamado teste.txt com os dados originais.
Todavia, se a senha estiver incorreta, cancela a execução do comando e aponta que a senha não está correta._

### Resultado Observado

![Captura de tela 2024-12-16 203952](https://github.com/user-attachments/assets/d826aa40-30f4-4c88-8ce8-2ea2e0cfedfa)


### Considerações Finais

Este projeto apresenta uma implementação simples de criptografia e descriptografia de arquivos utilizando Python. Ele permite observar a facilidade de criar ferramentas de criptografia (por mais que rudimentares), além da compreensão de conceitos como proteção de dados e o uso de chaves simétricas.
