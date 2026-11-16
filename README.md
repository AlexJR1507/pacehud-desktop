# PaceHUD Desktop

Programa gratuito para computador que acompanha o app **PaceHUD** (Android), um cronômetro de pista e navegador de rali. Neste repositório ficam apenas os instaladores; o código-fonte não é público.

**[Baixar a versão mais recente](https://github.com/AlexJR1507/pacehud-desktop/releases/latest)**

## O que ele faz

- **Comparar traçados:** coloca duas voltas ou duas passadas lado a lado e mostra, curva por curva, onde cada uma freou, a velocidade mínima, onde voltou a acelerar e quanto tempo ganhou ou perdeu. Veja em [pacehud.store/comparador](https://pacehud.store/comparador).
- **Análise das passadas e voltas:** velocidade, delta e dados do OBD-2 ao longo da pista, com o vídeo acompanhando o ponto escolhido.
- **Editor de pacenotes:** mapa, vídeo do reconhecimento e linha do tempo com o plano da voz.
- **Tela da volta e widget do vídeo:** monte no computador e envie ao celular.
- **Arrancadas (PaceHUD Drags) e viagens** recebidas do celular.

Os dados vêm do app PaceHUD no celular, pela tela **Conectar ao PC**, por cabo USB ou Wi‑Fi.

## Qual arquivo baixar

| Sistema | Arquivo | Como instalar |
|---|---|---|
| Windows 10/11 (64 bits) | `PaceHUD-Desktop-<versão>-windows-x64.msi` | Dois cliques. Se o Windows mostrar "O Windows protegeu o computador", clique em **Mais informações › Executar assim mesmo**: o instalador ainda não tem assinatura digital. Uma versão nova instala por cima da anterior. |
| Linux (qualquer distribuição x86-64) | `PaceHUD-Desktop-<versão>-linux-x64.tar.gz` | Extraia e rode `./install.sh`. Instala na sua pasta de usuário, sem `sudo`. |
| Ubuntu, Debian, Mint | `PaceHUD-Desktop-<versão>-linux-amd64.deb` | `sudo apt install ./PaceHUD-Desktop-<versão>-linux-amd64.deb` |
| Fedora, openSUSE | `PaceHUD-Desktop-<versão>-linux-x86_64.rpm` | `sudo dnf install ./PaceHUD-Desktop-<versão>-linux-x86_64.rpm` |

O manual completo (`Manual_PaceHUD.pdf`) acompanha cada versão.

**Opcional:**
- `ffmpeg`, para o vídeo do reconhecimento;
- no Linux, `espeak-ng`, para ouvir as frases (no Windows, a voz do sistema);
- `adb` do Android SDK (platform-tools), para conectar pelo cabo.

## Termos e privacidade

O uso segue os [Termos de uso](https://pacehud.store/termos) e a [Política de privacidade](https://pacehud.store/privacidade). As licenças das bibliotecas e fontes usadas acompanham o programa (menu ⋮ › Sobre o PaceHUD Desktop).

Contato: pacehud@gmail.com · [pacehud.store](https://pacehud.store)

© 2026 PaceHUD. Todos os direitos reservados.
