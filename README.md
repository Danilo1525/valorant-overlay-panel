# 🎯 Valorant Stream Overlay Generator

Um gerador de overlay leve, rápido e sem necessidade de banco de dados para streamers de Valorant. Crie, personalize e integre sua overlay de Rank e Status diretamente no OBS Studio em segundos!

## ✨ Funcionalidades

- **Painel de Controle Interativo:** Uma interface web moderna e escura (Dark Mode) para ajustar seus dados de stream.  
- **Preview em Tempo Real:** Veja exatamente como a overlay vai ficar no seu OBS antes mesmo de copiar o link.  
- **Integração 100% via URL:** Não requer banco de dados, login ou chaves de API restritas. Todos os dados viajam de forma segura pelos parâmetros da URL.  
- **Assets Oficiais:** Utiliza a API oficial de assets do Valorant (media.valorant-api.com) para garantir que os ícones de Rank (do Ferro ao Radiante) estejam sempre atualizados e em alta qualidade.  
- **Design Limpo e Responsivo:** Fundo transparente preparado nativamente para o OBS Studio, com tipografia fiel ao jogo.  

## 🚀 Como usar (Para Streamers)

1. Acesse o **$$Link do Gerador$$**  
   *[https://valorant-overlay-panel.vercel.app/](https://valorant-overlay-panel.vercel.app/)*

2. Preencha seus dados atuais no painel:
   - Rank  
   - RR atual  
   - Ganho/Perda  
   - Saldo de Vitórias/Derrotas  
   - Último Mapa  

3. O preview será atualizado instantaneamente.

4. Clique no botão **"Copiar Link"** no final da página.

5. Abra o **OBS Studio**:
   - Adicione uma nova **Fonte de Navegador (Browser Source)**  
   - Cole o link copiado no campo URL  
   - Defina:
     - **Width:** 400  
     - **Height:** 150  

6. Clique em **OK** e posicione a overlay na sua tela!

## 🛠️ Como hospedar o seu próprio gerador (Deploy)

Você pode hospedar este projeto gratuitamente e em poucos minutos usando a Vercel.

### Pré-requisitos

- Uma conta no GitHub  
- Uma conta na Vercel  

### Passo a passo

1. Faça um **Fork** deste repositório ou faça o upload dos arquivos (`index.html` e `README.md`) para um novo repositório no seu GitHub.  
2. Acesse sua conta na Vercel e clique em **Add New > Project**.  
3. Conecte sua conta do GitHub e selecione o repositório que você acabou de criar.  
4. Clique em **Import**.  
5. Nenhuma configuração extra é necessária! Apenas clique em **Deploy**.  

Em menos de 1 minuto, a Vercel fornecerá um link público permanente para o seu painel de controle.

## 📂 Estrutura do Código

O projeto foi construído para ser o mais simples possível, utilizando uma arquitetura **"All-in-One"** num único arquivo para facilitar a hospedagem estática.

- `index.html`: Contém a estrutura HTML, os estilos CSS incorporados (com variáveis dinâmicas) e o JavaScript responsável pela lógica de roteamento (Painel vs. OBS Mode) e manipulação dos parâmetros de URL.

## ⚠️ Aviso Legal (Riot Games)

Este projeto foi criado ao abrigo das políticas do "Linguagem Jurídica" (Legal Jibber Jabber) da Riot Games, utilizando propriedades intelectuais da Riot Games. A Riot Games não endossa nem patrocina este projeto.

O nome **"Valorant"**, os logótipos e os ícones de classificação (ranks) são marcas registadas ou marcas comerciais da Riot Games, Inc.

## 📝 Licença e Direitos Autorais

© Todos os direitos reservados sobre o código-fonte e interface do gerador. Este projeto (no que diz respeito ao código estrutural, lógica de programação e design da interface do painel) é de propriedade exclusiva do seu criador e **NÃO é de uso livre ou de código aberto (open-source)**.

É estritamente proibida a cópia, distribuição, reprodução, modificação, venda ou qualquer uso comercial/pessoal não autorizado da arquitetura deste código ou do design do painel sem a permissão prévia e expressa do autor.

> **Nota:** Esta restrição de direitos de autor aplica-se apenas ao código e design originais aqui desenvolvidos, não se sobrepondo aos direitos de propriedade intelectual da Riot Games mencionados acima.

---

Desenvolvido com 💚 para a comunidade de Valorant.
