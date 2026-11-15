# MatchCV

Uma aplicação web que utiliza inteligência artificial para analisar a compatibilidade entre um currículo e uma descrição de vaga, identificar palavras-chave relevantes e sugerir melhorias para tornar o currículo mais alinhado à oportunidade.

## Sobre o projeto

O MatchCV foi desenvolvido como parte de um desafio prático da DIO, com o objetivo de explorar o uso de inteligência artificial no processo de candidatura a vagas de emprego.

A proposta é ajudar profissionais a identificar pontos de alinhamento e oportunidades de melhoria em seus currículos, considerando os requisitos de uma vaga específica.

A ferramenta busca otimizar a apresentação das experiências e competências do candidato, sem inventar informações ou atribuir qualificações que não foram fornecidas.

## Funcionalidades

- **Análise de compatibilidade:** estimativa de alinhamento entre o currículo e a descrição da vaga.
- **Identificação de palavras-chave:** destaque dos termos encontrados e dos requisitos que podem estar ausentes no currículo.
- **Análise de competências:** identificação de habilidades técnicas e comportamentais relacionadas à oportunidade.
- **Recomendações de melhoria:** sugestões para tornar o currículo mais claro e aderente à vaga.
- **Otimização do currículo:** geração de uma versão revisada, preservando as informações e experiências reais do candidato.
- **Exportação em PDF:** possibilidade de exportar o currículo otimizado.

*Observação: a pontuação de compatibilidade é uma estimativa gerada pela ferramenta e não representa uma pontuação oficial de sistemas ATS nem garante aprovação em processos seletivos.*

## Demonstração da aplicação

Nesta seção, serão apresentados registros visuais das principais telas e funcionalidades do MatchCV.

**1. Tela inicial**

<img width="1355" height="638" alt="image" src="https://github.com/user-attachments/assets/cb96395a-2f0b-40b0-8c8b-df8a58a96b4c" />


**2. Análise de compatibilidade**

<img width="1356" height="634" alt="image" src="https://github.com/user-attachments/assets/a7144ba4-b083-41c8-a2e2-9eb151a59c49" />


**3. Palavras-chave identificadas**

<img width="1064" height="510" alt="image" src="https://github.com/user-attachments/assets/7139ee75-cbef-4c2c-86e5-200fa9b44e8a" />



## Tecnologias e ferramentas

- **Lovable:** desenvolvimento da aplicação com apoio de inteligência artificial.
- **React:** biblioteca para construção da interface.
- **TypeScript:** tipagem e organização do código.
- **Tailwind CSS:** estilização da aplicação.
- **shadcn/ui:** componentes de interface.
- **Lucide Icons:** biblioteca de ícones.

*As tecnologias e versões devem ser conferidas no código-fonte exportado pelo Lovable.*

## Desenvolvimento do projeto

O desenvolvimento foi conduzido a partir da definição de um problema, estruturação dos requisitos e criação de um prompt detalhado para orientar a construção da aplicação.

As principais etapas foram:

1. **Definição da proposta:** identificação da dificuldade de adaptar currículos às exigências específicas de cada vaga.
2. **Levantamento de requisitos:** definição das funcionalidades essenciais para a primeira versão.
3. **Construção do prompt:** detalhamento das regras de negócio, experiência do usuário, identidade visual e requisitos técnicos.
4. **Desenvolvimento no Lovable:** utilização da ferramenta para construir a aplicação.
5. **Validação e refinamento:** avaliação das telas e funcionalidades, com identificação de oportunidades de melhoria.

## Regras de negócio e confiabilidade

Um dos princípios centrais do MatchCV é preservar a veracidade das informações profissionais.

Por isso, a ferramenta deve:

- Não inventar experiências profissionais, habilidades, formações ou resultados.
- Não atribuir ao candidato competências que não estejam presentes nas informações fornecidas.
- Sugerir melhorias de escrita sem alterar o sentido das experiências relatadas.
- Considerar sinônimos e equivalências semânticas na identificação de palavras-chave.
- Apresentar o índice de compatibilidade como uma estimativa, e não como garantia de aprovação.

## Aplicação publicada

Acesse a aplicação: [MatchCV](https://matchcurriculum.lovable.app/)

## Próximas melhorias

- Aprimorar os critérios utilizados no cálculo de compatibilidade.
- Expandir a análise semântica de competências e requisitos.
- Melhorar a personalização das recomendações.
- Realizar testes com diferentes perfis profissionais e descrições de vagas.
- Aprimorar a formatação e a exportação do currículo em PDF.

## Considerações finais

O MatchCV é um projeto prático de aplicação de inteligência artificial para resolver um problema do cotidiano profissional.

Além do desenvolvimento da aplicação, o projeto envolveu estruturação de requisitos, definição de regras de negócio, elaboração de prompts e avaliação da experiência do usuário.

A iniciativa também permitiu explorar o potencial de ferramentas de desenvolvimento assistido por IA na construção de soluções digitais.
