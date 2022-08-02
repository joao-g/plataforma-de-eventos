## Plataforma de eventos

* [Informações gerais](#info-gerais)
* [Tecnologias](#tecnologias)
* [Configurações](#configuracoes)

## Informações gerais

* Este projeto trata-se de uma plataforma onde você pode exibir suas aulas durante um tempo determinado, essa aulas podem ser *gravadas* ou *ao vivo*, e também conseguimos pegar os emails e nomes dos participantes e armazenar dentro do **Graphcms**.

* Este projeto foi realizado na semana do **Ignite Lab** da rocketseat <https://www.rocketseat.com.br/> por meio de aulas ministradas pelo Diego Fernandes.

* Link para o repositorio da propria rockeseat: <https://github.com/rocketseat-education/ignite-lab-02>

* Abaixo temos um gif que demonstra o projeto.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/61668219/182459145-23e0c675-d891-43f5-82c2-ffc1d4460f49.gif)

## Tecnologias

As tecnologias utilizadas neste projeto são:

* Graphcms
* GraphQL
* Apollo GraphQL
* TailwindCSS
* React
* TypeScript
* Phosphor Icons
* Vime
* date-fns

## Configurações

* Para rodar este projeto em sua maquina, primeiro baixe este repositório ou clone o projeto, localize o arquivo e com o terminal aberto e com **NPM** instalado digite:

```bash
npm install
```

* Neste projeto foi utilizado o **Graphcms** <https://app.hygraph.com/a44846af82414b3fa9e39de0f10494d1/master/schema/model/Challenge/fields>, entrando neste link e se cadastrando tera acesso ao back-end pré-configurado do projeto.

* Crie um arquivo chamado '.env.local' na pasta principal do projeto, e dentro dele coloque:

```typescript
VITE_API_URL= "sua url do Graphcms"
VITE_API_ACCESS_TOKEN= "token da API do Graphcms"
```

* Realizado essas configurações, basta dar o comando abaixo e acessar a url no seu navegador <localhost:3000/>

```bash
npm run dev
```
