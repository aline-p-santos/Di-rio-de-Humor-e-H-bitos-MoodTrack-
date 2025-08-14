# Diario-de-Humor-e-Habitos

### Especificações Técnicas Obrigatórias:
Desenvolver uma aplicação web que permita ao usuário registrar diariamente seu humor (escala de 1 a 5) e hábitos concluídos (ex.: estudo, treino, leitura), exibindo gráficos semanais e mensais. O objetivo foi praticar conceitos de front-end e introduzir persistência local e visualização de dados.

### Tecnologias utilizadas:
- React;
- JavaScript (ES6+);
- HTML5;
- CSS3;
- LocalStorage (persistência de dados no navegador);
- Recharts (gráficos) — pode ser substituído por outra lib de charts.

### O que aprendeu:
Gerenciamento de Estado: composição de estados para formular e listar registros; uso de useState para inputs controlados;

Efeitos e Persistência: useEffect para salvar e carregar dados do localStorage sem backend;

Componentização: criação de componentes reutilizáveis como MoodSelector, HabitToggle, EntryList e ChartCard;

Props e Elevação de Estado: passagem de funções de atualização e dados entre componentes e “state lifting” para manter fonte única da verdade;

Renderização Condicional e Filtragem: mudança dinâmica de período (semana/mês), exibição de mensagens quando não há dados;

Visualização de Dados: integração de uma biblioteca de gráficos para linhas/colunas, mapeando os registros em séries temporais;

Acessibilidade e Responsividade: labels claros, navegação por teclado e layout fluido para mobile/desktop.
