# Atualização de Pontos de Venda (PDV) GNU/Linux

Este script é utilizado para a atualização e manutenção de pontos de venda (PDV) que utilizam o sistema operacional GNU/Linux, através de transferência via SSH.

## Funcionalidades

1. **Correção de Erros de Saque PIX:**
   - Remove arquivos específicos para corrigir problemas relacionados ao saque PIX e reinicia o PDV.

2. **Correção de Erros de Modo Gráfico:**
   - Remove arquivos que podem causar problemas no modo gráfico e reinicia o PDV.

3. **Atualização de Versão do PDV:**
   - Transfere arquivos de atualização para o PDV e executa um script de imagem para aplicar a atualização, seguido de um reinício do sistema.

4. **Menu de Opções:**
   - Oferece um menu interativo para selecionar diferentes operações de manutenção e atualização do PDV.

## Como Utilizar

1. **Requisitos:**
   - Certifique-se de ter `sshpass` instalado em seu sistema.

2. **Permissões:**
   - O script deve ser executado como usuário root ou com permissões sudo.

3. **Execução:**
   - Execute o script com o comando `./nome_do_script.sh`.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).


