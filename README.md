🎨 Background Generator para Devs Front-end 

Status do Projeto: 🚀Finalizado

Uma ferramenta inteligente que automatiza a criação de backgrounds dinâmicos. O diferencial técnico aqui é o uso do n8n como motor de lógica, separando a geração do estilo da interface visual.

📸 Preview

<img width="1345" height="908" alt="image" src="https://github.com/user-attachments/assets/b3d0f039-a051-426b-aba4-f7ea6d2f1660" />

_______________________________________________
🛠️ Diferenciais Técnicos:

•	Consumo de APIs: Integração entre Front-end e fluxos de automação.

•	Manipulação de DOM: Atualização em tempo real das propriedades CSS via JavaScript.

•	Arquitetura desacoplada: A lógica de geração de cores/gradientes não está no JS, mas sim no workflow do n8n.

🧪 Tecnologias e Ferramentas:
Tecnologia	      Função
n8n	Workflow      engine para geração dinâmica de estilos.
JavaScript	      Consumo de Webhooks e manipulação de estilos em tempo real.
HTML5/CSS3	     Estruturação e renderização visual responsiva.
______________________________________________
⚙️ Fluxo da Aplicação

1.	O n8n processa a lógica (ex: sorteio de cores ou padrões).
   
2.	O JavaScript faz uma requisição ao endpoint do workflow.
   
3.	A interface recebe os dados e injeta o CSS dinamicamente.
   
4.	O código é formatado e exibido para o usuário final.
   
🔗 Link para Testar

🌐 https://raypr5.github.io/fundo-magico/

