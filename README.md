# Cadastro de Usuário (Flutter)

Tela de cadastro de usuário desenvolvida em Flutter, com captura de dados, filtros de entrada, validação de campos e feedback visual.

**Aluno:** Renan Humberto
**Matrícula:** 2320880
**Disciplina:** Teste de Software, UniEVANGÉLICA

## Funcionalidades

- Campos: nome completo, e-mail, CPF, telefone e senha
- Formulário com `Form` e `TextFormField`
- Teclado adequado e `inputFormatters` (CPF e telefone aceitam só números)
- Validação campo a campo, com erros exibidos abaixo de cada campo
- `SnackBar` verde de sucesso quando o cadastro é válido

## Regras de validação

- Todos os campos são obrigatórios
- E-mail deve conter `@` e seguir um formato válido (RegExp)
- CPF com 11 dígitos e telefone com 10 ou 11 dígitos
- Senha com no mínimo 6 caracteres

## Desafio extra implementado

- Campo de confirmação de senha
- Botão para mostrar/ocultar a senha
- Validação de e-mail com RegExp
- `SnackBar` vermelho quando há campos inválidos

## Como executar

1. Instale o Flutter SDK
2. Clone o repositório
3. Na pasta do projeto, rode `flutter pub get`
4. Rode o app com `flutter run -d chrome`

## Estrutura

O código principal está em `lib/main.dart`.