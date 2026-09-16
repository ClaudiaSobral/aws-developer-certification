# ☁️ Diário de Estudos AWS

**Objetivo:** Registro prático dos laboratórios e cursos realizados no AWS Skill Builder.

## 🛡️ Dia 1: Configuração Segura da Conta (Fundamentos)
**Data:** 16/08

Antes de iniciar os laboratórios práticos, configurei a conta para garantir segurança e evitar cobranças acidentais do Free Tier.

### Ações Realizadas:
- [x] **Proteção da Conta Root:** MFA (Multi-Factor Authentication) ativado via aplicativo autenticador.
- [x] **Controle de Custos (Billing):** 
  - Alertas de uso do Free Tier ativados.
  - Alarme do AWS Budgets configurado para $0.01 (Zero spend budget).
  - Extra! Utilizei um cartão de crédito com limite pífio para o cadastro para que isso evite cobranças desnecessárias.
- [x] **Criação de Usuário IAM:**
  - Usuário administrador criado com permissão `AdministratorAccess`.
  - Senha customizada de acesso ao console definida.
  - Login testado com sucesso utilizando o Account ID de 12 dígitos.

### 📝 Notas e Aprendizados:
* **Regra de Ouro:** A conta Root (e-mail principal) nunca deve ser usada para o dia a dia. Todo o acesso operacional deve ser feito via usuário IAM.
* **ID da Conta:** Para logar com o IAM, a AWS exige primeiro o "endereço do prédio" (Account ID) para depois solicitar as credenciais do usuário.
* **Gestão de Custos:** Fechar a aba do navegador não desliga recursos. É obrigatório encerrar (terminate) serviços após os estudos para não consumir o Free Tier.

---