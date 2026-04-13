# GEA.
-Projeto GEA - Guia de Ensino e Aprendizado
  Este repositório contém o projeto de automação e modernização do Guia de Ensino e Aprendizagem (GEA) para o Itinerário Formativo do EMTI Propedêutico da Escola Geraldo Jardim Linhares.
-Sobre o Projeto:
  O projeto visa a automatização do preenchimento e gestão do GEA. O objetivo é substituir o processo manual (uso de arquivos Word e envios por e-mail) por uma interface web integrada a um banco de dados centralizado em planilha, garantindo a integridade dos dados e facilitando a análise pedagógica sistêmica.
-Detalhes Institucionais:
* Instituição: Escola Geraldo Jardim Linhares.
* Público-alvo: Professores e coordenação pedagógica do Ensino Médio em Tempo Integral (EMTI).
* Status: Em Desenvolvimento (Versão v1_30032026).
-Problemas Identificados (Processo Antigo)
* Processo Manual: Professores criam cópias de arquivos Word e as enviam por e-mail.
* Descentralização e Duplicidade: Com 4 coordenadores acessando o mesmo e-mail, geram-se múltiplas versões e risco de alteração nos originais.
* Análise Isolada: Os dados são analisados individualmente, dificultando uma visão geral da escola.
-Solução PropostaA nova implementação segue um fluxo digital estruturado:
1. Interface: O professor acessa uma interface web e preenche o formulário GEA.
2. Banco de Dados: As informações são armazenadas automaticamente em uma planilha centralizada.
3. Gestão: A coordenação acessa os dados através de uma interface de visualização para análise conjunta.
-Estrutura do Formulário (GEA 2026)
  O sistema captura as seguintes dimensões pedagógicas:
*Identificação: Nome, Turma, Componente Curricular e Trimestre.
* Desenvolvimento Curricular: Justificativa, Conteúdos IFA, Habilidades (Cognitivas e Socioemocionais), Valores e Competências para o Mundo do Trabalho.
* Metodologia: Situações didáticas e detalhamento de atividades (Prévias, Autodidáticas, Didático-Cooperativas e Complementares).
* Recursos e Avaliação: Práticas educativas, espaços utilizados, recursos didáticos, estratégias de avaliação e fontes de referência.
Implementação Técnica (v1)
  -A primeira versão utiliza Google Apps Script para gerar o formulário de coleta.
-Função Principal: gerarFormularioGEA()
  O script automatiza:
* A criação do Google Form com títulos e descrições automáticas.
* A organização por seções e quebras de página.
* A configuração de campos obrigatórios e textos de ajuda para orientar o preenchimento.
* A geração de logs com links para edição e resposta.
-Próximos Passos:
* Desenvolvimento de interface personalizada para acesso de professores e alunos.
* Expansão das funcionalidades de visualização de dados para a coordenação.
