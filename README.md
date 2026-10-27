# 📋 Portfólio de QA: Modelagem e Casos de Teste (End-to-End)

Este repositório apresenta um estudo de caso e suíte de testes funcionais desenvolvida para um fluxo completo de contratação de serviços, gestão de contas e gateway de pagamentos.

## 🚀 Sobre o Projeto
O objetivo foi estruturar cenários de teste cobrindo tanto caminhos felizes (*happy paths*) quanto fluxos de exceção e regras de negócio críticas (como tratamento de inadimplência, expiração de links e regras de senha).

## 📊 Estrutura da Suíte
A suíte contém **20 cenários de teste** documentados utilizando o padrão **BDD (Behavior-Driven Development)** com a estrutura `Given / When / Then`, facilitando a legibilidade e o alinhamento entre negócio, desenvolvimento e qualidade.

### Módulos Cobertos:
1. **Home & Catálogo:** Validação de exibição de planos promocionais.
2. **Formulário de Contato:** Validação de campos obrigatórios e envio com sucesso.
3. **Personalização de Planos:** Regras de modificação de combos (Plata, Oro e bloqueio no Bronce).
4. **Cadastro e Autenticação:** Preenchimento de dados, regra de usuário de acesso automático e complexidade de senhas.
5. **Ativação de Conta:** Validação de links dentro do prazo de 48h e tratamento de links expirados.
6. **Minha Conta (Regras de Negócio):** Cancelamento de pacotes com pagamento em dia vs. bloqueio de cancelamento para usuários inadimplentes.
7. **Gateway de Pagamento:** Transações bem-sucedidas, transações pendentes, cartões recusados e notificações/visitas técnicas.

---

## 📂 Arquivos Disponíveis
Você pode baixar e visualizar a planilha completa detalhada com os passos de execução e massas de dados aqui:
👉 **[Baixar/Visualizar Planilha de Casos de Teste](./Desenho_de_casos_de_teste_%28Formatacao_para_google_planilhas%29.xlsx)**

<img width="1749" height="630" alt="image" src="https://github.com/user-attachments/assets/93785c5f-e6c6-4efe-a0b5-248e0bb474fb" />
---
*Desenvolvido por Lucas Matos*
