# Desafio DevSecOps — Gerenciador de Tarefas

## Sobre o Projeto
Este repositório faz parte do desafio prático do módulo de DevSecOps da ADA Tech.
Você receberá este projeto com vulnerabilidades propositais e uma pipeline incompleta.
Seu objetivo é **implementar a pipeline de segurança** e **corrigir as vulnerabilidades**.

## Estado atual
A pipeline está **incompleta**. Os steps de segurança precisam ser implementados por você.

## Sua missão
1. Implementar os steps de segurança no `pipeline.yml`
2. Fazer a pipeline **quebrar** ao detectar os problemas
3. Corrigir as vulnerabilidades encontradas
4. Fazer a pipeline **passar** com tudo verde ✅
5. Documentar o funcionamento da pipeline neste README

## O que implementar
- [ ] Secrets Scanning com **Gitleaks**
- [ ] SAST com **Semgrep**
- [ ] SCA com **Grype**
- [ ] Deploy com **GitHub Pages**

## Como a pipeline funciona

Durante as aulas práticas, compreendemos o funcionamento do pipeline CI/CD. Os códigos foram inseridos com erros propositais, com o objetivo de demonstrar como as ferramentas de análise atuam na identificação de vulnerabilidades.

Ao detectar alguma falha, o processo é interrompido para que a correção seja realizada.

Utilizamos o recurso "Secrets and Variables - Actions" do GitHub para ocultar informações sensíveis. Após a execução do pipeline novamente, a ferramenta SAST "Semgrep", responsável pela análise estática do código, identificou novas vulnerabilidades. Após as devidas correções, o código passou a funcionar corretamente, e o GitHub Pages disponibilizou a URL com a aplicação em execução.

A ferramenta DAST também foi apresentada, permitindo observar a importância da análise de aplicações em tempo de execução, complementando a análise estática.

Durante o curso, conhecemos ferramentas relevantes, compreendemos a teoria e aplicamos o conhecimento na prática. Além disso, reforçamos a importância de analisar continuamente o código e todas as etapas do processo, incorporando a segurança desde o início, a fim de garantir que a aplicação esteja livre de vulnerabilidades antes de ser colocada em produção.

## URL de Produção
> Adicione aqui o link do GitHub Pages após o deploy.
https://dmoncano.github.io/projeto-devsecops-desafio/
