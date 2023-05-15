#  webcasas

![GitHub](https://img.shields.io/github/license/steinerstt/webcasas?style=for-the-badge)
![Website](https://img.shields.io/website?color=gree&label=Status&style=for-the-badge&up_message=finalizado&url=https://github.com/steinerstt/webcasas)
<br><br>


**
https://user-images.githubusercontent.com/106714068/228991465-1ef22d0c-a6bc-4a09-b721-9ac1680db73c.mp4

<br>

> A WebCasas é uma plataforma onde pessoas podem encontrar e/ou anúnciar imóveis para vender ou alugar.


**
## 🔰 Ao Vivo
Para acessar o deploy <a href="https://ziti.vercel.app/" target="_blank" > Clique Aqui! </a>

## 🌐 Api
<a href="https://github.com/steinerstt/api-webcasas" target="_blank"> API </a> criada por mim 

## 📌 Funcionalidades
- [x] Usuário
  - [x] Cadastro de usuário 
  - [x] Login de usuário
- [x] Pàgina inicial - "/"
  - [x] Listagem dos imóveis recentes 
  - [x] Listagem dos imóveis mais visualizados 
- [x] Paǵina dos imóveis - "/properties" 
  - [x] Listagem dos imóveis recentes
  - [x] Listagem dos imóveis de acordo com os filtros selecionados
  - [x] Filtros
    - [x] Estado e/ou cidade 
    - [x] Vender ou alugar
    - [x] Condomínio ou rua 
    - [x] Tipo de imóvel
    - [x] Detalhes do imóvel
 - [x] Página de atualizar cadastro - "/my-register"
   - [x] Atualizar dados de cadastro e/ou foto de perfil   
   - [x] Desativar conta
   - [x] Excluir conta
 - [x] Pàgina de ativar conta de usuário - "/active-account"
   - [x] Ativar conta
 - [x] Página de anúncios/imóveis do usuário - "/my-ads"
   - [x] Listagem dos anúncios/imóveis do usuário
   - [x] Desativar anúncio   
   - [x] Excluir anúncio
 - [x] Página para anúnciar um imóvel - "/form-property"
   - [x] Fomulário de anúncio 
- [x] Delogar
  

## 🛠️ Tecnologias
 Este projeto foi desenvolvido com as principais tecnologias
- NextJs
- TailwindCSS
- Chakra UI
- React-Icons
- React-Toastify
- TypeScript
- Axios
- Zod
- Nookies
- Zustand


## 🚀 Executando o projeto localmente

### 💻 Pré-requisitos
Para rodar o projeto é necessário que você tenha instalado na sua máquina as seguintes ferramentas:
- Git
- Node.js
- VSCode
- Yarn

### 💿 Rodando
```bash
# Clone este repositório através do terminal
$ git clone git@github.com:steinerstt/webcasas.git

# Acesse a pasta do projeto
$ cd webcasas

# Instale as dependências do projeto
$ yarn install

# Rode o projeto 
$ yarn dev
```
> *O projeto será executado rodando a API que está em produção, caso queira rodar o back-end na sua máquina, terá que seguir as instruções que estão no repositóio da <a href="https://github.com/steinerstt/api-webcasas" target="_blank"> API. </a> E também terá que alterar a baseUrl que está em: services > api.ts para a url local do back-end.

<br>

## 📸 Screenshots


![página-login](https://github.com/steinerstt/webcasas/assets/106714068/858d2112-0332-430a-8151-46ad24538629)
![página-cadastro](https://github.com/steinerstt/webcasas/assets/106714068/485978af-8c78-4f61-95a0-8cfedd6e458c)
![página-inicial](https://github.com/steinerstt/webcasas/assets/106714068/6435040d-a772-480a-bf64-5d5f8d2decac)
![página-inicial-logado](https://github.com/steinerstt/webcasas/assets/106714068/c77c4c24-3405-42ad-9807-a2832c89aad9)
![página-imóveis](https://github.com/steinerstt/webcasas/assets/106714068/4431e702-8e40-4a7d-8a35-4fea9be0327d)

![página-imóveis-filtros-aplicados](https://github.com/steinerstt/webcasas/assets/106714068/5258a470-2ccc-4b70-bfb8-34ba954a1813)
![página-imóveis-modal-filtros](https://github.com/steinerstt/webcasas/assets/106714068/21a8de08-f2e0-461c-9b65-f735fdeb9cb8)
![página-imóveis-estato-selecionado](https://github.com/steinerstt/webcasas/assets/106714068/a157a224-9461-44c7-8242-a33981556ba1)
![página-imóveis-menu-usuário-aberto](https://github.com/steinerstt/webcasas/assets/106714068/35ca3707-f88a-465b-a5f7-620334b1e296)
![página-meu-cadastro](https://github.com/steinerstt/webcasas/assets/106714068/ac14bee7-9d0b-4040-b7cd-e6ac5960e9e1)
![página-meu-cadastro-gerenciamento-conta-aberto](https://github.com/steinerstt/webcasas/assets/106714068/63c260bb-a575-40f5-8abc-ae017a08a45b)
![página-meu-cadastro-gerenciamento-conta-aberto-modal-desativar-conta](https://github.com/steinerstt/webcasas/assets/106714068/43940708-ac1c-46db-85b2-b926a744467c)
![página-meu-cadastro-gerenciamento-conta-aberto-modal-excluir-conta](https://github.com/steinerstt/webcasas/assets/106714068/479fe9f3-6cc5-4584-b7a7-b78e070fb115)
![página-ativar-conta](https://github.com/steinerstt/webcasas/assets/106714068/be60a7b5-7007-4ea7-8b4a-9c4f3242ce00)
![página-meus-anúncios](https://github.com/steinerstt/webcasas/assets/106714068/97d21a70-a794-4e8a-8641-277b8a52b787)
![página-meus-anúncios-modal-excluir-aberto](https://github.com/steinerstt/webcasas/assets/106714068/2d8ba92e-48f8-4d5d-ab68-bfa406abf7d3)
![página-meus-anúncios-modal-desativar-aberto](https://github.com/steinerstt/webcasas/assets/106714068/b0acfb62-ddf2-4f71-aad9-a774f3e42d1e)
![página-meus-anúncios-modal-ativar-aberto](https://github.com/steinerstt/webcasas/assets/106714068/eb1447c6-175c-4b66-8b92-e1e945146ac8)
![página-anunciar-imóvel](https://github.com/steinerstt/webcasas/assets/106714068/1b98ac0b-193f-4c3b-b283-0392b6eacd6d)


<br>!



## 📄 Licença
Este projeto está sob a licença do MIT - veja o arquivo [LICENSE](https://github.com/steinerstt/webcasas/blob/main/LICENSE) para detalhes.

Feito com ❤ por [Steiner](https://github.com/steinerstt)
