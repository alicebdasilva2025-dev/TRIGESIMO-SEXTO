# LiDire — VIGÉSIMO QUINTO

## Correção da lista de familiares
- Quando o e-mail já existe como membro da família no D1, o aplicativo agora sincroniza o registro existente para o estado local em vez de apenas mostrar uma mensagem e encerrar.
- O cadastro existente é atualizado/mesclado por ID do servidor ou e-mail, sem criar um duplicado.
- A tela da família é renderizada novamente após a sincronização.
- Preserva os demais arquivos do projeto da versão anterior e mantém a correção da migração D1 de `family_members.user_id`.

## Validação
A validação sintática deve ser executada antes da publicação. O comportamento final precisa ser testado no Worker e no D1 reais.
