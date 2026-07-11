# Análise da API de Portabilidade de Dados do TikTok à Luz da LGPD

Página desenvolvida como apoio à defesa do Trabalho de Conclusão de Curso intitulado:

> **Análise da Documentação da API de Portabilidade de Dados do TikTok à Luz da Lei Geral de Proteção de Dados Pessoais: um estudo sobre classificação e riscos no tratamento de dados pessoais**

## Acesso à apresentação

[🔗 Treegraph — API de Portabilidade de Dados](https://walfredo95.github.io/Treegraph-API-de-Portabilidade-de-Dados/)

## Sobre a pesquisa

Esta pesquisa analisa a documentação técnica da **API de Portabilidade de Dados do TikTok** sob a perspectiva da **Lei Geral de Proteção de Dados Pessoais — LGPD (Lei nº 13.709/2018)**.

O estudo busca compreender quais dados são disponibilizados pela API, como esses dados podem ser classificados e quais riscos podem surgir a partir de seu tratamento, compartilhamento e combinação.

A análise foi realizada a partir da documentação pública disponível na plataforma **TikTok for Developers**, considerando a versão consultada em **4 de junho de 2026**.

## Questão de pesquisa

> Quais tipos de dados são disponibilizados pela API de Portabilidade de Dados do TikTok e quais riscos estão associados ao tratamento desses dados a partir de sua classificação sob a perspectiva da LGPD?

## Objetivo geral

Analisar os dados disponibilizados pela documentação técnica da API de Portabilidade de Dados do TikTok, sob a perspectiva da LGPD, com foco na identificação, classificação e discussão dos potenciais riscos associados aos dados disponibilizados pela plataforma.

## Objetivos específicos

1. Identificar os tipos de dados disponibilizados pela API de Portabilidade de Dados do TikTok.
2. Classificar os dados identificados com base nos conceitos estabelecidos pela LGPD.
3. Discutir as implicações e os possíveis riscos associados ao tratamento e ao compartilhamento desses dados.

## Metodologia

A pesquisa caracteriza-se como:

- aplicada;
- qualitativa;
- exploratória;
- descritiva;
- documental.

A análise foi conduzida em três etapas:

1. **Identificação da estrutura da API**, por meio da leitura sistemática da documentação oficial do TikTok.
2. **Mapeamento e classificação dos dados**, com base em perguntas orientadoras elaboradas a partir dos conceitos da LGPD.
3. **Análise qualitativa dos riscos**, considerando identificação, perfilamento, inferência sensível, compartilhamento e localização.

Também foram analisados quatro endpoints responsáveis pelo processo de portabilidade:

- `Add Data Request`;
- `Check Status of Data Request`;
- `Cancel Data Request`;
- `Download`.

## Principais resultados

Foram identificados **211 campos de dados**, distribuídos em sete categorias:

| Categoria | Quantidade | Percentual |
|---|---:|---:|
| Dado Comportamental | 113 | 53,55% |
| Dado Financeiro | 47 | 22,27% |
| Dado Pessoal | 29 | 13,74% |
| Dado de Dispositivo | 6 | 2,84% |
| Dado com Potencial de Inferência Sensível | 6 | 2,84% |
| Dado de Localização | 5 | 2,37% |
| Dado de Pessoa Jurídica | 5 | 2,37% |
| **Total** | **211** | **100%** |

A maior parte dos dados disponibilizados pela API está relacionada ao comportamento do usuário dentro da plataforma, incluindo preferências, interações, histórico de navegação, buscas, curtidas, comentários, mensagens, compras e atividades associadas ao uso do TikTok.

## Riscos identificados

A pesquisa identificou cinco grupos principais de riscos potenciais:

1. **Perfilamento comportamental**  
   A combinação de dados sobre curtidas, buscas, comentários, interações e preferências pode permitir a reconstrução de parte do perfil do usuário.

2. **Identificação direta ou indireta**  
   Dados pessoais e identificadores técnicos podem tornar uma pessoa natural identificada ou identificável.

3. **Inferência de dados pessoais sensíveis**  
   Informações aparentemente não sensíveis podem, quando combinadas, permitir inferências sobre posicionamento político, crença religiosa, orientação sexual, saúde ou outras características protegidas pela LGPD.

4. **Compartilhamento com outros serviços**  
   Após a portabilidade, os dados podem ser submetidos a novas finalidades, políticas de privacidade, Termos de Serviço e mecanismos de tratamento.

5. **Reconstrução de localização**  
   Dados de localização, quando associados a outros registros, podem revelar rotas, locais visitados e padrões de mobilidade.

## Conclusão

Os resultados demonstram que a API de Portabilidade de Dados do TikTok disponibiliza um conjunto amplo e diversificado de informações.

Embora a portabilidade seja importante para a autonomia do titular e para a interoperabilidade entre serviços, a transferência e a combinação dos dados podem ampliar riscos relacionados à identificação, ao perfilamento, à inferência de informações sensíveis e à reconstrução de localização.

A principal contribuição do trabalho consiste na organização e interpretação dos campos documentados pela API do TikTok sob a perspectiva da LGPD, tornando mais visíveis riscos que nem sempre aparecem de forma clara na documentação técnica.

## Limitação da pesquisa

O estudo foi limitado à análise da documentação técnica e pública da API de Portabilidade de Dados do TikTok. Não foram realizadas requisições práticas à API nem coleta direta de dados de usuários.

## Autor

**Walfredo Avila dos Santos Filho**

- Curso: `Sistemas de Informação`
- Instituição: `Universidade Federal do Pará`
- Ano: **2026**

## Uso acadêmico

Este repositório foi desenvolvido para fins acadêmicos e para apresentação dos resultados do Trabalho de Conclusão de Curso.
