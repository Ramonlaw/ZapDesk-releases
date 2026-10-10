# ZapDesk

WhatsApp no seu computador, com agendamento de mensagens. Roda no Windows e abre no navegador que você já usa.

## Download

A versão mais recente está sempre em **[Releases](../../releases/latest)**. Baixe o arquivo `ZapDesk-x.y.z-instalador.exe`.

## Instalação

1. Execute o instalador e siga o assistente. Ele não pede senha de administrador.
2. Ao terminar, o ZapDesk abre no seu navegador padrão.
3. Na primeira vez, crie a sessão e escaneie o QR code com o celular: no WhatsApp, toque em **Dispositivos conectados** e depois em **Conectar dispositivo**.

Não é preciso reiniciar o computador. O Windows pode mostrar um aviso do SmartScreen por ser um programa novo; escolha **Mais informações** e depois **Executar assim mesmo**.

## Como usar

- Abra pelo atalho **ZapDesk** na Área de Trabalho ou no Menu Iniciar. O endereço é `http://localhost:2785`.
- O ZapDesk inicia sozinho junto com o Windows e continua funcionando com o navegador fechado. É isso que permite enviar as mensagens agendadas na hora marcada.
- O celular não precisa ficar ligado o tempo todo, mas o computador sim: mensagem agendada só sai com o PC ligado.

## Atualizações

Quando sai uma versão nova, o ZapDesk avisa na própria tela. Você escolhe quando atualizar e a troca leva poucos segundos. Suas conversas e a conexão com o WhatsApp são mantidas.

## Seus dados

Tudo fica no seu computador, em `%LOCALAPPDATA%\ZapDesk\data`. Nada é enviado para servidores do ZapDesk.

## Desinstalar

Em **Configurações > Aplicativos > Aplicativos instalados**, procure ZapDesk e escolha **Desinstalar**. A pasta `data` é preservada, para o caso de você reinstalar; apague-a à mão se quiser remover as conversas e a conexão.

## Suporte

Dúvidas ou problemas: abra uma [issue](../../issues).

## Créditos

- [@Ramonlaw](https://github.com/Ramonlaw) — criação e desenvolvimento
- [Claude](https://github.com/claude) (@claude)
- Powered by [OpenWA](https://github.com/rmyndharis/OpenWA), projeto de código aberto sob licença MIT.

---

© 2026 ZapDesk. Distribuído apenas em formato executável.
O ZapDesk não é afiliado ao WhatsApp nem à Meta. WhatsApp é marca registrada da Meta Platforms, Inc.
