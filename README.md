# GestArt – Sistema de Gestão de Projetos Culturais

Projeto acadêmico da disciplina **Modelagem de Software** (Centro Universitário UNA), com a proposta de um sistema web para gerenciar projetos culturais financiados pela **Lei Rouanet**.

**Equipe:** Adriele Pereira Santana, Fabiana Jerônimo de Lima, Igor Alves Rocha, Larissa Fernandes de Assis

![Capa da apresentação](imagens_apresentacao/slide-01-capa.png)

## Sobre o projeto

Produtores culturais lidam com muita burocracia e controle financeiro manual, e patrocinadores não têm visibilidade clara do andamento dos projetos que financiam. O GestArt centraliza essa gestão em uma única plataforma, com três perfis de usuário: **produtor**, **patrocinador** e **fornecedor**.

![Objetivos do sistema](imagens_apresentacao/slide-02-objetivos.png)

## Principais funcionalidades

- Cadastro e autenticação de usuários, com perfis de acesso
- Cadastro de projetos culturais (metas, orçamento, cronograma, equipe)
- Autorização de emissão de notas fiscais
- Balanço financeiro por projeto, com exportação em PDF/XLSX
- Relatório final de prestação de contas e histórico de projetos

![Exemplo de caso de uso](imagens_apresentacao/slide-03-caso-de-uso.png)

## Modelagem

- Levantamento de requisitos funcionais e não funcionais (com matriz de rastreabilidade)
- 7 casos de uso em UML (gerenciar perfis, cadastrar usuário/projeto, autenticar, gerenciar equipe, autorizar NF, balanço financeiro)
- Diagrama de classes
- Modelo entidade-relacionamento (notação de Chen)
- Simulação de banco de dados relacional (Excel) e consultas SQL
- Protótipo das telas (login, dashboard, cadastro de projeto, gerenciamento de equipe, autorização de NF, balanço financeiro)

![Protótipo da tela de login](imagens_apresentacao/slide-04-tela-login.png)

## Documentos neste repositório

- `Gestart-ModelagemDeSoftware.pdf` — documento completo (requisitos, casos de uso, diagramas, banco de dados e consultas SQL)
- `A3_ModelagemSoftware.pdf` — slides de apresentação (recomendado: abrir em nova aba/baixar para ver na horizontal, já que o preview do GitHub às vezes distorce PDFs widescreen)
