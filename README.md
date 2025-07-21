# Sistema de Controle de Estacionamento para Hotéis

> Projeto desenvolvido como solução de mensageria para o controle de entrada e saída de veículos em hotéis.  
> Feito com Laravel. O código-fonte completo está disponível em outro repositório.

---

## Sobre o Projeto

Este sistema foi criado para facilitar a operação de mensageiros/manobristas em hotéis, otimizando o registro, consulta e gerenciamento de veículos em tempo real. A aplicação centraliza informações relevantes para auditoria e operação, além de garantir segurança e rastreabilidade dos dados.

---

## Funcionalidades

### 1. Autenticação
- Sistema de cadastro e login com autenticação segura.

### 2. Dashboard
- Visão geral das operações recentes.

### 3. Check-in de Veículos
- Registro de veículos com os seguintes dados:
  - Mensageiro responsável
  - Nome do hóspede
  - Modelo, cor e placa do carro
  - Número do apartamento
  - Número da credencial
  - Observações gerais
  - Localização da chave (gaveta, balcão ou com o hóspede)
  - Checkbox para sinalizar se o hóspede entrou direto (sem dados)

### 4. Consulta de Veículo
- Busca rápida pelo número do apartamento.
- Exibe os dados do veículo mais recente em check-in.

### 5. Histórico de Veículos
- Tabela completa com todos os registros de check-in e checkout.
- Exportação em PDF para fins de auditoria.
- Edição de registros para atualizar dados em caso de mudanças (ex: troca de chave ou apartamento).

### 6. Checkout de Veículos
- Listagem de todos os veículos em check-in com botão de checkout individual.

### 7. Gerenciamento de Mensageiros
- Área restrita apenas à gerência.
- Cadastro e administração de mensageiros/manobristas.

---

## Imagens do Sistema

### Tela de Check-in
[Tela de Check-in](assets/checkin.png)


### Histórico de Veículos
[Histórico de Veículos](assets/historico.png)


### Checkout
[Checkout](assets/checkout.png)


---

## Tecnologias Utilizadas

- Laravel (PHP)
- Blade Templates
- MySQL
- Tailwind
- DomPDF (para exportação em PDF)

---

## Autor

**Desenvolvido por mim**  
Dev formado em Análise e Desenvolvimento de Sistemas   

---

## 📬 Contato

Fique à vontade para entrar em contato caso tenha dúvidas, sugestões ou oportunidades.

---

