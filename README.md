# rocketseat_app_finan-as

Vamos desenvolver um aplicativo de gestão de orçamento mensal. O objetivo é criar uma aplicação que permita o cadastro, listagem e remoção de transações e orçamentos, cálculo de débitos e saldos mensais.
Instruções
Estrutura, regras e requisitos do projeto

1. Estrutura inicial
Crie um projeto no *Swift utilizando como base os aprendizados obtidos no projeto Reminder.
As tecnologias que serão utilizadas são:
XCode
UIKit
Firebase
Podfile
Cocoapods
2. Funcionalidades obrigatórias
📱Splash Screen
A Splash deve conter pelo menos uma animação de entrada e transição para LoginView.
🔐 Autenticação e gestão de perfil
Deve ser possível autenticar o usuário via email/senha.
Deve ser possível salvar os dados do usuário no dispositivo ao logar-se.
Deve ser possível revelar e ocultar senha.
Deve ser possível autenticar-se com o Face ID.
Deve ser possível fazer logout.
Deve ser possível alterar foto de perfil do usuário.
🏦 Orçamentos e transações
Deve ser possível cadastrar orçamento mensal.
Deve ser possível remover orçamento mensal.
Deve ser possível visualizar dados do orçamento mensal do mês atual no Dashboard:
Saldo final: Créditos mensais + Débitos mensais;
Usado: Débitos mensais;
Limite: Orçamento designado para o mês;
O cartão ilustrativo deve apresentar uma barra de progresso de quanto foi gasto no mês em relação ao limite.
Deve ser possível cadastrar uma transação com título, categoria, valor, data e tipo (entrada ou saída).
Deve ser possível visualizar os dados de descrição, ícone de categoria, data da transação, valor e tipo ilustrado por seta colorida de cada transação em uma tabela.
Deve ser possível ver o número de transações do mês no cabeçalho da tabela.
Deve ser possível remover uma transação.
Deve ser possível notificar o usuário sobre as transações que ocorrerão no dia atual (o horário de envio fica a critério do desenvolvedor).
3. Desafios extras
🗓️ Seletor e Carossel de meses
Com o seletor de meses é possível navegar entre os meses e visualizar as transações e orçamentos de cada um. Para criar tal efeito pode-se usar a UICollectionView que o professor ensina no próximo módulo, por isso é um desafio opcional.

Vídeo de exemplo da funcionalidade

🗑️ Deleção de transação e orçamento com arraste
Em vez de fazer a deleção com o toque do botão da lixeira que tal adicionarmos uma micro-interação com um efeito de arraste?! Para fazer a deleção com arraste você pode utilizar o PanGesture nativo em Swift.

Vídeo de exemplo da funcionalidade

4. Interface (baseada no layout do Figma)
O layout deve ser feito com base no Figma do projeto. Após ele ser finalizado, se sinta livre para publica-lo e realizar alterações, mas para o desenvolvimento do desafio, se atenha ao que temos especificado no Figma.

Caso queira um gostinho de como o app pode ficar, temos um vídeo da solução dele 
aqui
.

5. Desenvolvendo o projeto
Para desenvolver esse projeto, recomendamos utilizar as principais ferramentas que utilizamos durante o desenvolvimento do primeiro módulo da formação.

Caso você tenha alguma dificuldade você pode ir no nosso 
fórum
 e deixar sua dúvida por lá!

Após terminar o desafio, caso você queira, você pode tentar dar o próximo passo e deixar a aplicação com a sua cara. Tente mudar o layout, cores, ou até adicionar novas funcionalidades para ir além 🚀

6. Entrega
Lembre-se que o intuito de um desafio é te impulsionar, por isso, dependendo do desafio, pode ser que você precise ir além do que foi discutido em sala de aula. Mas isso não é algo ruim: ter autonomia para buscar informações extras é uma habilidade muito valiosa e vai ser ótimo pra você treinar ela aqui com a gente!

E lembre-se: tenha calma! Enfrentar desafios faz parte do seu processo de aprendizado!

Após concluir o desafio, você deve enviar a URL do seu código no Github.

Além disso, que tal fazer um post no LinkedIn compartilhando o seu aprendizado e contando como foi a experiência?

É uma excelente forma de demonstrar seus conhecimentos e atrair novas oportunidades!

Obs: Se você se sentir à vontade, pode postar um print do resultado final e nos marcar! Vai ser incrível acompanhar a sua evolução! 💜

Feito com 💜 por Rocketseat 👋
