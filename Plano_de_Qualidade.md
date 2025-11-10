# Plano de Gerenciamento da Qualidade

## Nome do Projeto
**Aplicativo de Gerenciamento de Tarefas para Desenvolvedores**

## Equipe

- **Ycaro Entriel** – Gerente de Projeto  
---

## 1. Objetivos de Qualidade
- Garantir que o aplicativo mantenha taxa de defeitos inferior a 2% após o lançamento.  
- Assegurar cobertura mínima de 95% das funcionalidades com testes automatizados.  
- Alcançar nota de 90% ou superior em testes de usabilidade.  

---

## 2. Requisitos de Qualidade

**Funcionalidade:** O sistema deve permitir o gerenciamento completo de tarefas com autenticação de usuários.  
**Desempenho:** O tempo médio de resposta deve ser inferior a 1 segundo.  
**Segurança:** Senhas criptografadas e comunicação via HTTPS.  
**Usabilidade:** Interface responsiva e intuitiva para desktop e mobile.  

---

## 3. Papéis e Responsabilidades

**Gerente de Projeto:** Ycaro Entriel  
**Desenvolvedores:** Maria Silva  
**Equipe de QA:** João Costa  
**Designer:** Ana Pereira  

---

## 4. Processos de Qualidade
- Revisões de código obrigatórias antes do merge.  
- Execução automática de testes via integração contínua.  
- Reuniões semanais para avaliação da qualidade.  

---

## 5. Métricas de Qualidade

**Cobertura de testes:** 95% de código coberto por testes automatizados.  
**Taxa de defeitos:** Máximo de 2 bugs críticos por versão.  
**Tempo de correção:** Correção de bugs críticos em até 48 horas.  

---

## 6. Plano de Testes

**Testes unitários:** Implementados com JUnit e Mockito.  
**Testes de integração:** Executados com Spring Boot Test e banco em memória.  
**Testes funcionais:** Realizados com Selenium e Postman.  
**Testes de desempenho:** Monitorados com JMeter.  

---

## 7. Ferramentas de Qualidade
- SonarQube para análise estática de código.  
- JUnit e Mockito para testes automatizados.  
- GitHub Actions para integração contínua.  

---

## 8. Auditorias e Revisões
- Auditorias mensais de código e qualidade.  
- Revisões ao final de cada sprint para melhorias contínuas.  

---

## 9. Treinamento e Capacitação
- Workshops sobre práticas de desenvolvimento ágil.  
- Capacitação em ferramentas de QA e CI/CD.  

---

## 10. Gerenciamento de Riscos

**Risco 1:** Atrasos devido a problemas de integração.  
**Mitigação:** Usar integração contínua e revisões de código frequentes.  

**Risco 2:** Falhas de segurança em autenticação.  
**Mitigação:** Aplicar validações e monitoramento contínuo de vulnerabilidades.  

---

## 11. Documentação
- Manual do usuário e documentação da API REST.  
- Histórico de versões e registro de alterações.  

---

## 12. Feedback e Melhoria Contínua
- Coleta de feedback através de formulários e métricas de uso.  
- Implementação de melhorias com base em relatórios de auditoria.  
