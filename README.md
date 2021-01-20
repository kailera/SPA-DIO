# SPA---Desenvolvendo-SPA-com-Angular
## Aula ministrada pela professora Camila Ribeiro Ferreira - 19/01/2021

#### Componentes:
Shared
-header
-content
-footer

Components
-sedans
-pickups
-suvs

#### Components do Angular Material Utilizados:
MatToolbarModule,    
MatIconModule,
MatTabsModule,
MatCardModule,
MatDialogModule


Neste projeto criei um SPA de mostra de carros de 3 seguimentos. As paginas são alternadas pelas tabs localizada no component content. Assim, a página não é atualizada, mantendo o conceito de Single Page Aplication. Cada componente mostra varios cards de um seguimento de veículos (sedans, pickups e suvs), cada card com um botão de curtir que habilita um MatDialog para confirmação da Ação. Para fins de aprendizado, apliquei o property biding nas tabs, onde os textos das labels vem do componente.ts, e nos eventos de click das tabs e dos MatDialogs. Apliquei o roteamento padrao inicial no onInit do content.component.ts para a primeira aba a ser sempre mostrada ser a página dos sedans. 

Posteriormente posso aplicar slideshows de veículos e um sistema de votação para os carros mais votados.
