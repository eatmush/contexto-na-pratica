# Contexto na prática

Um passo a passo interativo, no navegador, que mostra para pessoas não
técnicas como trabalhar com um **repositório de contexto**: uma pasta de
arquivos de texto que o Claude lê em toda conversa, para que a IA comece
cada sessão já sabendo do seu assunto.

O site simula uma tela de VS Code com o Claude Code. A pessoa clica em
"Próximo" e acompanha um exemplo completo, a reforma de um apartamento:

1. **O problema:** a IA do chat esquece tudo entre uma conversa e outra.
2. **Montando:** criar a pasta, rodar o Claude Code e gerar o `CLAUDE.md`
   a partir de uma entrevista.
3. **Uma semana depois:** a mesma pergunta do chat, agora respondida com
   os dados da pessoa.
4. **Guardando:** `/debrief` para registrar o que importa e `/backup` para
   salvar uma cópia.
5. **Sua vez:** um guia real de instalação e o roteiro de criação pronto
   para copiar.

Não precisa de cadastro nem de instalação para usar.

## Status

Versão 0, ainda em teste com as primeiras pessoas do público.

## Como rodar

É um único `index.html`, sem build e sem dependências. Abra o arquivo no
navegador ou sirva a pasta com qualquer servidor estático.

## Licença

[MIT](LICENSE)
