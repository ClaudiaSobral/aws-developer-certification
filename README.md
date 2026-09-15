# aws-developer-associate

[![AWS Certified Developer Associate](https://img.shields.io/badge/AWS-Certified%20Developer%20Associate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/certification/certified-developer-associate/)

---

> Repositório de estudos para apoio à certificação AWS Certified Developer - Associate (DVA-C02)

## ❇️ O que é esse repositório?

Esse é meu registro público para auxiliar os estudos para a prova de certificação AWS Certified Developer - Associate. Assim como fiz durante a preparação para a [DP-600 (Fabric Analytics Engineer)](https://github.com/ClaudiaSobral/dp-600-fabric-analytics-engineer), esse é meu compromisso público com a prova e o registro do meu progresso semanal até a data do exame.

A base do meu estudo será o [AWS Developer Learning Plan (português)](https://skillbuilder.aws/learning-plan/8ZTS6X8W2U/aws-developer-learning-plan-portugus/BGT389JBTZ), disponível gratuitamente no AWS Skill Builder.

E que melhor maneira de se preparar do que se comprometer publicamente, não é mesmo?

## ❇️ Habilidades que serão adquiridas ao final do curso

O exame DVA-C02 é organizado em 4 domínios de conteúdo:

- **Development with AWS Services (32%)** — desenvolvimento de aplicações usando APIs, AWS CLI e SDKs dos serviços AWS (Lambda, API Gateway, DynamoDB, S3, entre outros).
- **Security (26%)** — implementação de autenticação, autorização e gerenciamento de segredos em aplicações na AWS (IAM, Cognito, KMS, Secrets Manager).
- **Deployment (24%)** — preparação e implantação de aplicações usando práticas modernas de CI/CD (CodePipeline, CodeDeploy, CodeBuild, SAM, CDK).
- **Troubleshooting and Optimization (18%)** — otimização de aplicações e depuração de problemas usando ferramentas de observabilidade (CloudWatch, X-Ray).

## ❇️ Objetivos

- 📚 **Aprendizado contínuo**: estarei atualizando esse repositório até a data da prova, com base no aprendizado do dia.
- 🧠 **Fixação do conteúdo**: resumos do conteúdo serão minha principal ferramenta para revisar e fixar o aprendizado em cada domínio do exame.
- 📈 **Demonstração do que foi aprendido**: laboratórios e simulados serão um apoio para o objetivo final, que vai além da certificação: conseguir aplicar profissionalmente todo o conteúdo da AWS Developer Associate.

## ❇️ O que você vai encontrar aqui?

- 📅 Calendário de estudos
- ⏰ Countdown para a prova
- 📝 Laboratórios e anotações por domínio
- 🛡️ Badges conquistadas

## ❇️ Calendário de estudos

> ⚠️ A trilha do Skill Builder é renderizada via JavaScript, então não consegui extrair automaticamente a lista exata de cursos/carga horária. As linhas abaixo são um ponto de partida com a estrutura típica do Developer Learning Plan — confirme nomes e durações direto na [página da trilha](https://skillbuilder.aws/learning-plan/8ZTS6X8W2U/aws-developer-learning-plan-portugus/BGT389JBTZ) e ajuste a tabela.

| Status | Trilha / Curso | Data de conclusão | Duração | Link |
| ------ | -------------- | ------------------ | ------- | ---- |
| 🔴 | Domínio 1 — Development with AWS Services | | | [Acesso à trilha](https://skillbuilder.aws/learning-plan/8ZTS6X8W2U/aws-developer-learning-plan-portugus/BGT389JBTZ) |
| 🔴 | Domínio 2 — Security | | | [Acesso à trilha](https://skillbuilder.aws/learning-plan/8ZTS6X8W2U/aws-developer-learning-plan-portugus/BGT389JBTZ) |
| 🔴 | Domínio 3 — Deployment | | | [Acesso à trilha](https://skillbuilder.aws/learning-plan/8ZTS6X8W2U/aws-developer-learning-plan-portugus/BGT389JBTZ) |
| 🔴 | Domínio 4 — Troubleshooting and Optimization | | | [Acesso à trilha](https://skillbuilder.aws/learning-plan/8ZTS6X8W2U/aws-developer-learning-plan-portugus/BGT389JBTZ) |
| 🔴 | Exam Prep: AWS Certified Developer - Associate (DVA-C02) | | | [Acesso à trilha](https://skillbuilder.aws/learning-plan/8ZTS6X8W2U/aws-developer-learning-plan-portugus/BGT389JBTZ) |

Legenda: 🔴 não iniciado · 🟡 em andamento · 🟢 concluído

## Data da prova: 31/10 (previsão)

[![Contador Regressivo](countdown.svg)](countdown.svg)

## Estrutura do repositório

```
├── .github/workflows/countdown.yml   # Action que atualiza o countdown.svg todo dia
├── 01-development-with-aws-services/ # Anotações e labs do domínio 1
├── 02-security/                      # Anotações e labs do domínio 2
├── 03-deployment/                    # Anotações e labs do domínio 3
├── 04-troubleshooting-and-optimization/ # Anotações e labs do domínio 4
├── imgs/                             # Imagens usadas no README
├── contador.py                       # Script que gera o countdown.svg
└── countdown.svg                     # Countdown até a data da prova
```
