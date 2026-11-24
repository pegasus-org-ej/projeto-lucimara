# Estrutura do Curso

## Visão geral

**Projeto:** Projeto E-learning  
**Curso:** Segurança do Paciente na Atenção Primária à Saúde (APS)  
**Cliente:** Lucimara  
**Ferramenta de autoria:** Adobe Captivate Classic  
**Status:** Concluído

O curso foi desenvolvido para capacitar profissionais da Atenção Primária à Saúde a reconhecer riscos assistenciais, aplicar práticas seguras e fortalecer a cultura de segurança do paciente no contexto da APS. O projeto integra o trabalho de mestrado da cliente.

## Público-alvo

Profissionais da Atenção Primária à Saúde, incluindo enfermeiros, médicos, técnicos e auxiliares de enfermagem, agentes comunitários de saúde e demais integrantes da equipe multiprofissional, respeitando as atribuições de cada categoria.

## Organização e percurso de aprendizagem

O conteúdo apresenta uma avaliação diagnóstica inicial, seis módulos de aprendizagem e uma avaliação final.

Os módulos devem ser realizados sequencialmente. O próprio curso orienta o aluno a concluir o módulo anterior antes de avançar.

### Avaliação diagnóstica

Antes dos módulos, o aluno realiza um pré-teste para identificar conhecimentos prévios sobre Segurança do Paciente na APS. O material informa que essa avaliação tem caráter diagnóstico e não punitivo.

### Módulos

| Ordem | Módulo | Tema |
|---:|---|---|
| 1 | Identificação Correta do Paciente | Identificação segura do paciente nos atendimentos da APS |
| 2 | Comunicação Efetiva | Comunicação entre profissionais e continuidade segura do cuidado |
| 3 | Segurança no Uso de Medicamentos | Práticas para reduzir riscos relacionados à utilização de medicamentos |
| 4 | Cirurgia Segura na APS | Cuidados de segurança em pequenos procedimentos realizados na APS |
| 5 | Prevenção de Infecções | Medidas de prevenção e controle de infecções |
| 6 | Redução de Lesões por Pressão e Quedas | Avaliação de riscos e estratégias preventivas |

O conteúdo exportado também apresenta quizzes de fixação ao longo dos módulos e telas de conclusão de módulo. Esses recursos fazem parte da experiência de aprendizagem construída no Captivate.

### Avaliação final

Após concluir os módulos, o aluno realiza a avaliação final, composta por cinco questões de múltipla escolha.

O conteúdo informa que é necessário obter pelo menos 70% de aproveitamento para aprovação.

### Certificado

O curso informa que o certificado de participação é emitido para os alunos que alcançarem o mínimo de 70% na avaliação final.

O repositório contém o arquivo `certif.html`, que apresenta o certificado em HTML. Nele, o nome do participante e a data podem ser editados diretamente na página, e o certificado pode ser impresso pelo botão disponível ou pelo comando de impressão do navegador.

## Recursos próprios do Captivate

A experiência do curso utiliza recursos disponibilizados pelo Adobe Captivate, incluindo:

- mapa do curso;
- navegação entre telas e módulos;
- quizzes e avaliações;
- elementos interativos incorporados ao conteúdo.

Esses recursos são parte da exportação HTML5. A documentação não descreve cada interação individual, pois sua configuração pertence ao projeto de autoria do Captivate.

Não há integrações externas com LMS, SCORM ou xAPI informadas para este projeto.

## Estrutura dos arquivos exportados

A estrutura observada no repositório é:

```text
projeto-lucimara/
├── ar/
│   └── Mouse.mp3
├── assets/
│   ├── TOC_icons/
│   ├── css/
│   ├── htmlimages/
│   ├── img/
│   ├── js/
│   └── toc/
├── dr/
│   └── arquivos JSON de recursos
├── certif.html
├── goodbye.html
├── index.html
├── project.txt
└── LICENSE
```

### Arquivos e diretórios

| Caminho | Responsabilidade |
|---|---|
| `index.html` | Ponto de entrada da exportação HTML5. Inicializa o runtime e carrega os recursos necessários para executar o curso. |
| `assets/` | Recursos utilizados pela exportação, incluindo folhas de estilo, scripts, imagens, ícones e arquivos relacionados à navegação. |
| `assets/js/` | Scripts de execução exportados pelo Captivate e biblioteca JavaScript utilizada pelo conteúdo. |
| `dr/` | Arquivos JSON de dados e recursos carregados durante a execução do curso. |
| `ar/` | Recursos de áudio presentes na exportação. |
| `certif.html` | Página HTML do certificado de conclusão. |
| `goodbye.html` | Página de encerramento apresentada ao sair do conteúdo. |
| `project.txt` | Arquivo de dados gerado pelo Captivate, contendo metadados e estrutura do projeto exportado. |
| `LICENSE` | Arquivo de licença mantido no repositório. |

Os diretórios internos de `assets/` e `dr/` são gerados e utilizados pela exportação do Captivate. Evite renomear, mover ou remover arquivos desses diretórios manualmente, pois o HTML e os scripts de execução dependem dos caminhos e recursos exportados.

## Autoria e manutenção

O arquivo-fonte editável do Adobe Captivate (`.cptx`) está com a cliente e não está presente neste repositório.

Consequências para manutenção:

1. Para editar telas, conteúdo, interações, mapa do curso ou avaliações, é necessário solicitar à cliente o arquivo-fonte original.
2. As alterações devem ser realizadas no Adobe Captivate Classic.
3. Após a edição, deve ser gerada uma nova exportação HTML5.
4. A exportação deve preservar os caminhos e arquivos necessários à execução do curso.
5. O certificado HTML deve ser revisado separadamente quando houver mudanças nas informações nele apresentadas.

Não é recomendado tentar reconstruir o projeto editável apenas a partir dos arquivos exportados. A exportação contém os recursos de execução, mas não substitui o arquivo-fonte de autoria.

## Publicação e repositórios

Este repositório pertence à organização da Pegasus e contém os arquivos do projeto mantidos pela equipe.

O repositório possui GitHub Pages configurado e apresenta o curso por meio da página inicial `index.html`.

Foi informado que existe também uma cópia em um repositório da cliente, com conteúdo em comum e uma página HTML inicial adicional para direcionar o acesso ao curso. Entretanto, o endereço desse repositório não está disponível; por isso, ele não é identificado nem descrito como parte desta documentação.

Ao atualizar os arquivos deste repositório, considere que a cópia da cliente é independente e não deve ser presumida como atualizada automaticamente.

## Limites conhecidos

- O arquivo-fonte `.cptx` não está armazenado neste repositório.
- Não há endereço confirmado do repositório mantido pela cliente.
- Não foram informadas integrações externas com LMS, SCORM ou xAPI.
- Não foi fornecido manual de identidade visual ou material de branding específico para documentar.
- Não há pendências conhecidas para o projeto concluído.

