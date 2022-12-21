# Trabalho 1 - Fundamentos de Sistemas Embarcados
## Sobre
Este trabalho tem por objetivo a criação de um sistema distribuído de automação predial para monitoramento e acionamento de sensores e dispositivos de um prédio com múltiplas salas. O sistema deve ser desenvolvido para funcionar em um conjunto de placas Raspberry Pi com um servidor central responsável pelo controle e interface com o usuário e servidores distribuídos para leitura e acionamento dos dispositivos. Dentre os dispositivos envolvidos estão o monitoramento de temperatura e umidade, sensores de presença, sensores de fumaça, sensores de contagem de pessoas, sensores de abertura e fechamento de portas e janelas, acionamento de lâmpadas, aparelhos de ar-condicionado, alarme e aspersores de água em caso de incêndio.

Mais especificações em: [Trabalho 1 da disciplina de Fundamentos de Sistemas Embarcados (2022/2)](https://gitlab.com/fse_fga/trabalhos-2022_2/trabalho-1-2022-2)

## Instruções
Para rodar o software, após clonar o repositório siga os seguintes passos para execuçao:

* Passo 1: Para inicializar o servidor central vá para o diretório: src/servers/central e execute o seguinte comando:
```
$ python server.py
```

* Passo 2: Escolha o arquivo de config que será utilizado no servidor central: 
<img width="835" alt="Captura de Tela 2022-12-21 às 11 10 02" src="https://user-images.githubusercontent.com/40725728/208925597-e8f7569c-3029-4b6a-b22a-7c99fefb885c.png">

* Passo 3: Em seguida para inicializar o servidor distribuido vá para o diretório: src/servers/distribuido e execute o seguinte comando:
```
$ python server.py
```
* Passo 4: Repita a mesma configuração do passo 2 só que agora para o servidor distribuido: 
<img width="835" alt="Captura de Tela 2022-12-21 às 11 10 02" src="https://user-images.githubusercontent.com/40725728/208925597-e8f7569c-3029-4b6a-b22a-7c99fefb885c.png">

* Passo 5: No servidor central escolha entre as ações disponiveis: 
<img width="938" alt="Captura de Tela 2022-12-21 às 11 16 35" src="https://user-images.githubusercontent.com/40725728/208926172-cd4b2939-d6eb-4711-9da9-02dc56a3aa3a.png">


