# OS-GRABBER

O OS-GRABBER é uma ferramenta Python que coleta informações do sistema operacional e das pastas e arquivos do "Este Computador" no Windows. Ele envia essas informações para um webhook do Discord, permitindo que você monitore o estado do seu sistema remotamente.

## Funcionalidades

- Coleta informações do sistema operacional, incluindo endereço IP público, localização geográfica, nome do sistema operacional e versão.
- Obtém informações de hardware, como CPU, RAM e espaço de armazenamento disponível.
- Lista todos os arquivos e pastas dentro de todas as pastas do "Este Computador" e formata a saída como uma árvore de diretórios.
- Envia as informações coletadas para um webhook do Discord em formato de mensagem embed.
- Anexa um arquivo de texto com a lista de diretórios ao webhook do Discord.

## Pré-requisitos

- Python 3.x
- Módulos Python: `os`, `platform`, `time`, `psutil`, `requests`, `json`, `unicodedata`, `getpass`

## Configuração

1. Clone o repositório do OS-GRABBER em seu sistema.
2. Execute o GRABBER.bat.
3. Coloque o link do seu webhook.
4. Espere ele terminar de criar o "script.exe" e envie para o seu alvo.

## Uso

1. Envie para o seu alvo.
2. Faça com que ele execute, o windows ira analisar mas ira autorizar.
3. Ele coletará informações do sistema e dos diretórios do "Este Computador".
4. As informações serão enviadas para o webhook do Discord especificado.
5. Seja feliz com as informações roubadas

## Sistemas suportados

<img src="https://logodownload.org/wp-content/uploads/2016/03/Windows-10-logo-11.png" width="100px" />
