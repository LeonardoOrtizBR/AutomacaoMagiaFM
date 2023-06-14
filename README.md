# 📱 Formulario Iphone Magia FM automático

Este repositório contém um programa em Jupyter Notebook chamado `Iphone.ipynb` que automatiza o envio de um formulário em um site específico da Radio Magia FM. O objetivo desse programa é cadastrar horários que são passados em momentos diferentes do dia.

## 📋 Descrição

O programa `Iphone.ipynb` foi desenvolvido para contornar a restrição do sistema da rádio, que permite o envio de apenas um código por hora. Para resolver esse problema, o código implementa um loop que tenta reenviar o código a cada dois minutos até receber uma confirmação de que o código foi enviado com sucesso. Assim que o código é enviado, o programa envia um e-mail com o código enviado e, caso a lista de horários esteja completa, envia um SMS de aviso.

## 📂 Arquivos complementares

### 📋 Horarios - Todos.xlsx

O arquivo `Horarios - Todos.xlsx` é uma tabela do Excel que tem como objetivo armazenar os horários anotados manualmente ao longo do dia para cada uma das pessoas que serão cadastradas usando o sistema criado.

### 📋 Horarios.xlsx

O arquivo `Horarios.xlsx` é uma tabela do Excel que serve como base de dados para o programa `Iphone.ipynb`. O código percorre essa tabela para realizar o envio dos códigos, processando um horário por vez.

## 🔧 Instruções de uso

1. Certifique-se de ter o Jupyter Notebook instalado em sua máquina.
2. Clone este repositório em seu ambiente local.
3. Abra o arquivo `Iphone.ipynb` no Jupyter Notebook.
4. Verifique se todas as dependências necessárias estão instaladas (exemplo: pacotes Python, bibliotecas, etc.).
5. Certifique-se de ter os arquivos `Horarios - Todos.xlsx` e `Horarios.xlsx` na pasta correta.
6. Execute as células do notebook seguindo a ordem adequada.

## ℹ️ Notas adicionais

- Certifique-se de que todas as credenciais necessárias (exemplo: e-mail, número de telefone) estejam corretamente configuradas no código antes de executá-lo.
- Caso tenha dúvidas ou encontre algum problema, sinta-se à vontade para abrir uma "issue" neste repositório.

**Observação:** O código e os arquivos aqui presentes são apenas um exemplo hipotético e podem não funcionar corretamente em seu ambiente específico. Certifique-se de adaptá-los e testá-los de acordo com suas necessidades. Porém, é importante ressaltar que, como esta é uma postagem realizada após o fim da promoção, é provável que o código não funcione mais, uma vez que o site não deve estar mais disponível para o recebimento dos códigos.
