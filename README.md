# Bambino - Acompanhamento do Bebê

## Sobre o Aplicativo

Bambino é um aplicativo móvel desenvolvido para ajudar mães e cuidadores a acompanhar as atividades diárias do bebê, focando em dois aspectos essenciais:

- Registro de fraldas (úmidas, sujas ou mistas)
- Registro de mamadas (duração e lado do peito)

## Funcionalidades Principais

### 1. Registro de Fraldas
- Registro rápido com um toque
- Três tipos de fralda:
  - 💧 Úmida
  - 💩 Suja 
  - 🔄 Mista
- Registro automático de data e hora

### 2. Registro de Mamadas
- Controle da duração da mamada
- Seleção do lado do peito (esquerdo/direito)
- Registro de horário personalizado
- Registro automático de data

### 3. Histórico Completo
- Visualização cronológica de todas as atividades
- Organização por data e horário
- Ícones intuitivos para cada tipo de registro
- Fácil identificação do tipo de atividade

## Tecnologias Utilizadas

- React Native
- Expo
- SQLite (armazenamento local)
- React Navigation

## Benefícios

- Interface intuitiva e fácil de usar
- Registro rápido com poucos toques
- Funciona offline (todos os dados ficam no dispositivo)
- Design noturno para uso durante a madrugada
- Animações suaves para melhor experiência do usuário

## Como Usar

1. Na tela inicial, escolha entre:
   - Registrar Fralda
   - Registrar Mamada
   - Ver Histórico

2. Para registrar uma fralda:
   - Selecione o tipo (Úmida, Suja ou Mista)
   - O horário é registrado automaticamente

3. Para registrar uma mamada:
   - Selecione o lado do peito
   - Digite a duração em minutos
   - Ajuste o horário se necessário

4. Para consultar o histórico:
   - Acesse a opção "Histórico"
   - Visualize todos os registros organizados por data e hora

## Instalação

```bash
npm install
npm start
