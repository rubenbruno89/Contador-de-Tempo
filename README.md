# Contador de Tempo até o Horário Alvo

## Descrição
Este projeto é um contador de tempo simples que exibe a hora atual e permite que o usuário defina um horário alvo. Quando o horário alvo é selecionado, o contador exibe o tempo restante em minutos e segundos até que o horário seja alcançado. O objetivo é criar uma experiência visual agradável e intuitiva para gerenciar contagens regressivas para horários específicos.

## Funcionalidades
- **Relógio Atualizado**: Exibe a hora atual e atualiza automaticamente a cada segundo.
- **Contagem Regressiva**: Permite definir um horário alvo e conta o tempo restante em tempo real.
- **Interface Intuitiva**: Interface responsiva e minimalista, com destaque em gradiente para uma experiência visual agradável.
- **Notificação de Tempo Esgotado**: Informa o usuário quando o tempo restante atinge zero.

## Estrutura do Projeto
- **HTML/CSS**: Estrutura da interface e estilização da página.
- **JavaScript**: Scripts para atualizar o relógio, calcular a contagem regressiva e manipular a exibição dinâmica do tempo restante.

## Uso
1. Abra o arquivo `index.html` em um navegador.
2. O relógio exibirá a hora atual automaticamente.
3. Insira o horário alvo no campo de entrada e clique em **"Iniciar Contagem"**.
4. O contador começará a contagem regressiva até o horário selecionado.
5. Quando o tempo expirar, o contador exibirá a mensagem "Tempo esgotado!".

## Estrutura do Código
- **HTML**: Estrutura de layout do relógio, campo de entrada para horário alvo e botão de iniciar.
- **CSS**: Estilos para personalização visual, incluindo gradientes e sombras.
- **JavaScript**:
  - `updateClock()`: Função para exibir e atualizar a hora atual.
  - `startCountdown()`: Função para iniciar a contagem regressiva com base no horário alvo inserido.
  - `updateCountdown()`: Função para atualizar o tempo restante até o horário alvo e exibir "Tempo esgotado!" quando atinge zero.

## Licença
Este projeto está licenciado sob a licença MIT.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.
