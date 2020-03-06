# VTEX IO
The template repository for the Store Framework course on Learning Lab.

https://vtex.io/

## VTEX IO Toolbelt

```sh
yarn global add vtex
```

## Start new projct

Usando o seu terminal, navegue até um diretório de arquivos locais já existente para o qual deseja copiar o Tema da Loja. Em seguida, use o comando vtex init , selecione a opção store-theme e confirme que deseja fazer download da pasta do tema para o destino que você acabou de escolher.

```sh
vtex init
```

## Vtex login

Depois que a CLI do VTEX IO estiver instalada, você poderá fazer login na sua conta VTEX com o seguinte comando. Por sua vez, isso abriria uma janela do navegador solicitando suas credenciais.

```sh
vtex login {account}
```

## Workspaces

Ao usar o VTEX IO, qualquer interação com uma conta acontece em um espaço de trabalho . Ao fazer login em uma loja, você está automaticamente em seu espaço de trabalho principal, o que significa que está na versão disponível para o usuário final. Portanto, lembre-se sempre de criar uma área de trabalho de desenvolvimento usando o comando vtex use sempre que desejar testar uma nova configuração.

```sh
vtex use {examplename}
```

```sh
https://{workspace}-{account}.myvtex.com
```

#### Listas

```sh
vtex workspace list
```

## Link

Agora que o Store Theme foi copiado para sua pasta local, você deve executar o cd store-theme no seu terminal. Depois, execute o link vtex para que o tema seja compilado e publicado na conta e no espaço de trabalho que você acabou de criar.

```sh
vtex link
```

## Whoami

Execute vtex whoami para ter certeza de que você está na conta certa e em um espaço de trabalho de desenvolvimento. Caso contrário, o Toolbelt não aceitará o link diretamente com o espaço de trabalho principal.

```sh
vtex whoami
```

## Abrir url no browser

```sh
vtex browse
```