# arquitetura-de-componentes-Angular

Projeto desenvolvido para exemplificar os tipos de data binding do Angular.

## Arquitetura de componentes
A arquitetura de componentes baseia-se na construção de componentes
independentes, substituíveis e modulares que auxiliem no
gerencianciamento da complexidade e encorajem a reutilização.

#### Benefícios

> Escalabilidade

> Manutenção

> Performance

### Serviços

> Responsáveis por organizar e compartilhar lógica de negócios

> Reutilizáveis entre diferentes componentes de uma aplicação

> Mandatorios para um arquitetura modular e reutilizável

### Injeção de Dependência

Todo serviço é uma dependência que precisa ser instanciada dentro do
componente para ser utilizada pelo mesmo. No angular, o componente
pede para aplicação quais dependências ele precisa e então as injeta
dentro de si.

### Ciclo de vida de um componente

Todo componente possui seu ciclo de vida (normalmente chamado de
lifecycle hooks), que começa assim que o Angular o instancializa na
aplicação e através deles é possível executar diferentes lógicas nos vários
estágios de um componente.
