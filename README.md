🌱 Projeto EcoMonitor 👥 Identificação do Grupo Integrantes: Ana Luiza, Samuel, Natali, Nicolas, Gabriel

Formação: Analise e Desenvolvimento De Sistemas e Ciências da Computação

Matéria: IHCUX

🧠 Princípios de Usabilidade (Heurísticas de Nielsen) O desenvolvimento foi guiado por critérios de usabilidade para garantir uma interface amigável:

Status do Sistema: Através da atualização do contador em tempo real, o usuário tem ciência total do processamento de suas ações no sistema.

Resposta Instantânea: O uso de feedback imediato (atualização de barras e números) assegura que o usuário perceba o êxito de sua interação no momento do clique.

Padronização e Estética: A interface utiliza componentes consistentes, o que reduz a curva de aprendizado e torna a navegação intuitiva.

🚀 Instruções para Inicialização Siga o passo a passo abaixo via CLI para rodar a aplicação:

Restaurar dependências:

Bash Restauração dotnet Executar a aplicação:

Bash dotnet run --launch-profile https Acesso: Abra o seu navegador no link indicado no terminal (ex: https://localhost:xxxx).

🛠️ Detalhes do Desenvolvimento Técnico A arquitetura do sistema foca na reutilização de código. O componente central, EcoStatus, faz uso da diretiva [Parameter] do Blazor para receber dados dinâmicos.

Parâmetros configuráveis:

Título: Personaliza o rótulo da atividade ambiental.

Peso: Estipula a pontuação atribuída a cada interação.

Exemplificação de instanciamento:

Razor CSHTML Essa abordagem elimina a redundância de código (DRY - Don't Repeat Yourself) e simplifica futuras manutenções ou expansões do painel.

📊 Recursos da Interface Gestão de estado individualizada por card.

Pontuação variável conforme o tipo de ação.

Indicador visual de progresso.

Gatilho de meta (conclusão aos 100 pontos).

Feedback textual de conquista ao finalizar o objetivo.

📝 Conclusão Este trabalho exercita a criação de componentes modulares e o controle de estados dinâmicos dentro do ecossistema Blazor, resultando em uma aplicação organizada, funcional e focada na experiência do usuário.
