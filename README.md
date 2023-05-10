# Automação em Python

Mini Projeto de automação em Python, para baixar uma base de dados, pegar os indicadores, realizar cálculos e enviar para os e-mails necessários.

## Como adaptar o código para cada usuário:

- A biblioteca pyautogui trabalha com posições x e y para saber onde realizar os cliques, portanto, para adaptar o código para seu PC, é necessário modificar os parâmetros de x e y nas linhas que apresentam o comando  pyautogui.click().<br>
  Para auxiliar, o comando pyautogui.position() indica a posição x e y atuais.

- É necessário adicionar, na mesma pasta onde contém o código, um arquivo chamado emails.txt, conténdo um email por linha. Dessa forma o script consegue ler o arquivo de texto e puxar os e-mails necessários a serem enviados.
