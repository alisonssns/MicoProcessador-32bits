# MicoProcessador-32bits

![image](https://github.com/user-attachments/assets/ef361419-f7b6-4a7e-8ba8-5e34bc5b7a4b)

## Objetivo
Como atividade da Materia de Arquitetura de Software, foi proposto o desafio de criar um processador mico de 32BITS que realizasse a maioria das instruções da tabela abaixo, o processador deveria ser feito com circuitos integrados no aplicativo [Digital](https://github.com/hneemann/Digital) e deveria conter uma ULA, um Banco de Registradores e um Controle. Segue abaixo, a lista de especificações do projeto.

[Projeto.pdf](https://github.com/user-attachments/files/18916919/lista.pdf)

![Tabela de instruções](https://github.com/user-attachments/assets/9cb4c94f-2fe9-4bcf-8b63-c12eabbf7870)

## Uso

### Clone o repositorio
```bash
git clone https://github.com/alisonssns/MicoProcessador-32bits
```

### Inicialize o Digital
- Execute o aplicativo ```digital.exe```, vá em **Arquivos**, logo em seguida em **Abrir** e procure pelo arquivo ```MicoProcessador.dig``` na pasta **Componentes**
- Por fim, clique em **Iniciar a simulação do circuito**

## Funcionalidade
1. Inicialmente o processador irá realizar dois addi, adicionando os numeros [14, 4] ao banco de registradores
2. Em seguida irá realizar na ordem: Soma, Subtração, Multiplicação, "AND", "OR", "XOR", "SLT", "NOT", "LD", "ST", "SHOW a", "JR", "BEQ".
3. E finaliza travando a execução com um "HALT"
