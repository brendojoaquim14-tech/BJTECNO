# Site institucional — BJ Tecnologia

Pacote pronto para publicação por GitHub e Railway.

## Publicar no GitHub

1. Crie um repositório novo no GitHub.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Não envie somente o arquivo ZIP: extraia-o antes.

## Publicar no Railway

1. No Railway, selecione **New Project**.
2. Escolha **Deploy from GitHub repo**.
3. Selecione o repositório criado.
4. O Railway reconhecerá automaticamente o `Dockerfile`.
5. Aguarde a implantação ficar com o status **Success**.
6. Em **Settings > Networking**, clique em **Generate Domain**.

## Usar bjtecno.com.br

1. No serviço do Railway, abra **Settings > Networking > Custom Domain**.
2. Informe `bjtecno.com.br`.
3. O Railway mostrará o registro DNS necessário.
4. No Registro.br, abra o domínio e entre em **DNS > Configurar zona DNS**.
5. Cadastre exatamente o registro informado pelo Railway.
6. Aguarde a validação do domínio e a emissão automática do certificado HTTPS.

Se o Railway solicitar CNAME no domínio principal e o Registro.br não permitir,
use `www.bjtecno.com.br` no Railway e redirecione o domínio principal para `www`.
