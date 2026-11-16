# Dopamine — modo de demonstração

Esta cópia foi configurada para executar somente uma simulação visual do fluxo de jailbreak.

- O botão continua respeitando a checagem de compatibilidade do projeto.
- O fluxo mostra progresso e logs marcados como `[SIMULAÇÃO]`.
- A rotina `DOJailbreaker` real não é chamada neste build.
- Nenhum exploit, bootstrap, alteração de arquivos do sistema, privilégio, respring ou reboot é executado.
- Ao final, a aplicação informa explicitamente que nada foi instalado.

Os componentes originais foram preservados no projeto para manter a estrutura do Xcode, mas o caminho acionado pela interface está protegido por `DOPAMINE_SIMULATION_ONLY`.
