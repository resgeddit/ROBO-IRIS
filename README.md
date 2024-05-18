### Projeto Íris
Uma bot em português feita para PC, originalmente para o grupo Legião Z no WhatsApp, possui mais de 150 comandos e continua em crescimento e melhorias frequentes.

### Usar apenas no Telefone
No celular é dificílimo que você consiga usar, portanto, use o site [Goorm](https://ide.goorm.io) para criar sua BOT pelo telefone, mas saiba que ele irá te desconectar frequentemente, se você possui PC, é muito melhor usa-lo do que usar o Goorm.

### Pedido Pessoal
- Por favor NÃO REMOVA os créditos, levei muito tempo e precisei ter muita dedicação pra se criar uma BOT Brasileira assim, agradeço pela cooperação.

### Erros & Bugs
Se notar erros leia a [Discussions](https://github.com/KillovSky/iris/discussions), se ela não resolver, fale comigo pelos meios no final da pagina ou reporte no Issues, e claro, se certifique de ter instalado chrome e de ler TUDO que estiver escrito abaixo.
Baixe Chrome no Windows por [aqui](https://www.google.com/chrome), no linux use os comandos abaixo.

```bash
> wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
> sudo apt install ./google-chrome-stable_current_amd64.deb
```

### Para os donos
Você pode rodar comandos de Windows como "ipconfig", comandos de linux como "apt", ou comandos de programações como python -c tudo pelo WhatsApp, ninguém além de você pode usar isso, se você deseja que usem, remova a linha if (!isOnwer) [aqui](https://github.com/KillovSky/iris/blob/main/config.js#L3169), mas saiba que remove-la pode ser perigoso a você.

### Funções (Não são todas, +150)

| Função |Contém|
| ------------- | ------------- |
| Pausar BOT |✅|
| XP, Ranking, Level |✅|
| Bloquear/Desbloquear pessoas |✅|
| Puxar alguns dados |✅|
| Usar CMD/Terminal pelo WhatsAPP |✅|
| Anti-Fake/Blacklist |✅|
| Downloads (Redes-Sociais e YouTube) |✅|
| Conversar por texto/voz Sim-Simi/Local (ilimitado) |✅|
| Busca/fotos de animes |✅|
| Wikipédia |✅|
| Brainly |✅|
| Nasa |✅|
| Buscar anime por foto |✅|
| Stickers em imagem |✅|
| Ataques SMS |✅|
| Mandar mensagens a outro PV (por comando) |✅|
| Comandos de zoeira |✅|
| Prints de tela e sites |✅|
| Geração de textos |✅|
| Mensagem para Todos |✅|
| Sair de tudo |✅|
| Deletar todas as mensagens |✅|
| Revogar links de grupo|✅|
| Adicionar/remover pessoas |✅|
| Tirar ADM |✅|
| Anti porno/links de grupos |✅|
| Sticker/Sticker GIF |✅|
| Stickers sem fundo/Por palavra/Link |✅|
| Fabrica de meme/Pegar memes |✅|
| Busca de pinterest |✅|
| Construção de "diario" em foto |✅|
| Silenciar grupo para administradores |✅|
| Falar frases em 51 idiomas |✅|
| Mudar foto do grupo |✅|
| Marcar todos |✅|
| Stalkear instagram/twitter |✅|
| Google/Google Play |✅|
| Pesquisa por foto |✅|
| Upload de fotos em nuvem |✅|
| Tradutor |✅|
| Boas Vindas e Adeus |✅|
| Deletar mensagens do bot |✅|
| Remover todos |✅|
| Votações (Urna) |✅|
| Foto de garotas, macacos, etc |✅|
| Informações de Grupo/Perfil |✅|
| Outros (Lista tem mais de 130) |✅|

### Requisitos

- [NodeJS](https://nodejs.org) - Recomendo a LTS.
- [Git](https://git-scm.com) - Opcional (Se não usar Git Clone).
- [Ffmpeg](https://ffmpeg.org) - Para o comando de GIF.
Se desejar, pode tentar instalar o ffmpeg usando o npm, siga o código abaixo:

```bash
> npm i fluent-ffmpeg -g
```

Para a instalação do git, node e ffmpeg em Linux, use o comando abaixo:

```bash
> sudo apt install nodejs git ffmpeg -y
```

Caso você obtenha erros com a versão do node no repositório de seu Linux, use o [Node Source](https://github.com/nodesource/distributions), lembre-se de usar a LTS (14).

### Instalação
Você precisa ter esse repositório, é simples, rode os comandos abaixo, em caso de erros, rode como sudo/administrador.

```bash
> git clone https://github.com/KillovSky/iris.git
> cd iris
> npm i
```

### Iniciar
Para iniciar digite o comando abaixo e espere, após isso, escaneie o QR Code.

```bash
> npm start
```

### Ver todos os comandos
Digite no seu chat a mensagem:

```bash
> /menu
```

### Crie seus comandos
Há uma base simples para suas criações por [aqui](https://github.com/KillovSky/iris/blob/main/config.js#L3464), basta que você remova a "/\*" e a "\*/" para utilizá-la, se precisar de outros tipos, você pode ver sobre eles por [aqui](https://docs.openwa.dev/classes/client.html), se obtiver dificuldades, chame-me por [aqui](https://chat.whatsapp.com/H53MdwhtnRf7TGX1VJ2Jje) ou [aqui](https://wa.me/+5518998044132).

### Mudanças
Edite as API's encontradas em: (Se estiver incorreta avise ou procure)

- [API 1](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#5)
- [API 2](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#6)
- [API 3 & 4](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#4)
- [API 5](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#7)
- [Limite de Membros](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#9)
- [Limite de Grupos](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#8)
- [Prefix](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#4)
- [Número 1 & 2](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#2)
- [DDI](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#3)
- [Bomber](https://github.com/KillovSky/iris/blob/main/config.js#L3156)
- [Akinator](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#11)
- Elas são referentes aos sites [RemoveBG](https://www.remove.bg/pt-br), [ImgBB](https://api.imgbb.com/) e [AlphaCoders](https://wall.alphacoders.com/api.php)
- A DDI e Akinator são obrigatórios apenas caso você for de fora do Brasil, o Bomb apenas se você usar Linux.

### Brainly Português
Depois de terminar a instalação siga esses passos para deixar seu brainly em português:

```
Abra a brainly.js na pasta iris\node_modules\brainly-scraper\src
Mude a graphql/id para graphql/pt
```

### Computer-Freaker/Axios
Para fixar o funcionamento da API da Computer-Freaker, que é responsável por diversos comandos (hug, hentai, dva, baguette...), siga os passos desse [Mini-Tutorial](https://github.com/KillovSky/iris/discussions/10).

### Alertas no WhatsApp
Para receber também as mensagem de erros da Íris pelo WhatsApp, remova a "//" da linha [Catch](https://github.com/KillovSky/iris/blob/main/config.js#L3520).

## Agradecimentos a:
- [Open-WA](https://github.com/open-wa)
- [ArugaZ](https://github.com/ArugaZ)
- [MhankBarBar](https://github.com/MhankBarBar)
- [Tio das Trevas](https://github.com/TioDasTrevas)
- [Jon](https://github.com/Jonn001)
- [SlavyanDesu](https://github.com/SlavyanDesu)
- Agradeço de coração a todos vocês!

## Doar e Suporte
- [Doações] - Ajude-me a criar comandos, doe algo pelo PicPay ❤️ - [Doar](https://picpay.me/userlucas123)
- [PIX] - fc270199-2d55-4d91-be5c-bfbd431cfad4
- [Grupo Oficial] - Não somos grupos de travas - [Entrar](https://chat.whatsapp.com/H53MdwhtnRf7TGX1VJ2Jje)
- [Dono] - Se precisar falar comigo - [Falar](https://wa.me/+5518998044132)
