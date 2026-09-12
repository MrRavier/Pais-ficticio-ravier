# Auditoria de realismo histórico e estilo — implementada

> **Status:** implementada na segunda edição do cânone de 1920–1979. As correções aprovadas foram incorporadas a `historia/`, `resumos/`, `personagens/` e consolidadas em `retcons/retcon-geral-1920-1979.md`.

## Problemas identificados na primeira edição

A primeira versão apresentava seis problemas principais:

1. **demografia soviética superestimada**, chegando a 185 mil em 1959 e mais de 200 mil em 1979 sem migração que justificasse esses números;
2. **expansões territoriais fáceis demais**, tratadas como simples decisões administrativas sem disputas por arquivos, quadros, kolkhozes, redes elétricas, escolas e orçamento;
3. **violência rural subestimada entre 1944 e 1953**, concentrando resistência armada quase inteiramente em Ants Kaldre;
4. **repressão pós-Stalin repetitivamente moderada**, com quase todos os casos terminando em advertência ou transferência profissional;
5. **democracia pré-1940 excessivamente funcional**, com poucos escândalos, greves, corrupção, contrabando, violência de rua ou conflito linguístico real;
6. **prosa e nomenclatura com sinais de geração por IA**, incluindo metanarração, antíteses simétricas, instituições com nomes didáticos e excesso de personagens perfeitamente bilíngues/mistos.

## Correções implementadas

### Demografia
A série foi refeita. O censo de 1959 passa a trabalhar com cerca de **114 mil habitantes** e o de 1979 com cerca de **126 mil**, em vez de 185 mil e 207–210 mil.

### 1920–1939
Foram incorporados contrabando, corrupção aduaneira, patronagem, contratos questionados, greves ferroviárias com feridos, atraso salarial, falências, conflito escolar, antissemitismo, violência política e a crise armada de 1934. A república continua parlamentar, mas não é apresentada como administração exemplar ou imune às tensões da região.

### 1940
A condição de **17ª República da União** ganhou justificativa institucional: Moscou preserva temporariamente a antiga unidade soberana para sustentar a ficção de adesão voluntária e evitar uma partilha imediata entre Estônia e Letônia. A desproporção burocrática passa a ser reconhecida dentro da própria história.

### 1944–1953
A resistência armada foi ampliada para várias células independentes. Foram adicionados ataques, mortes de funcionários e informantes, bunkers, infiltrações, prisões e pressão sobre famílias. Ants Kaldre permanece importante, mas deixa de representar sozinho todo o movimento.

### Fronteiras soviéticas
As transferências de 1948–1957 passam a ocorrer por decretos, presidiums, raions, selsoviets e comissões de delimitação. As unidades administrativas modernas são usadas apenas como equivalência cartográfica. Tallinn e Riga resistem burocraticamente às perdas de território e recursos.

### 1956
A transformação da RSS Carelo-Finlandesa em república autônoma passa a provocar revisão do status de Valga–Valka. A fusão é abandonada porque o território já reúne antigas áreas estonianas e letãs e uma nova divisão reabriria a questão fronteiriça.

### Repressão pós-Stalin
Foram introduzidos casos concretos de prisão, expulsão universitária, busca domiciliar, perda de licença profissional, punição a familiares, campo de trabalho e um caso secundário de psiquiatria política. O padrão continua menos violento que o stalinismo, mas deixa de ser uniformemente brando.

### Instituições e termos
A segunda edição substituiu ou reclassificou nomenclaturas artificiais:

- censura republicana → escritório local/republicano do **Glavlit**;
- órgão econômico de 1957 → **Sovnarkhoz**;
- “Programa Republicano de Qualidade” → **Resolução nº 48 do Conselho de Ministros sobre perdas, devoluções e qualidade da produção**;
- “Memorando Cultural de Võru” → carta coletiva sem título oficial;
- “Cadernos da Fronteira” → nome historiográfico retrospectivo para folhas datilografadas sem título fixo;
- “Petição dos Sete” → rótulo posterior para a carta de 1976;
- “Lei de Salvaguarda Constitucional” → **Lei de 22 de junho sobre Associações Armadas, Armas e Ordem Pública**.

### Personagens e nomes
Foram reduzidos sobrenomes excessivamente compostos e biografias simbolicamente equilibradas. Principais mudanças:

- Arnold Vahtramäe → **Arnold Kask**;
- Māra Lehtmets → **Māra Kalniņa**;
- Liidia Kõivamäe → **Liidia Sikk**;
- Ilmārs Vaher → **Ilmārs Vītols**;
- Jānis Kaur → **Jānis Kalējs**;
- Andres Ziediņš → **Andrejs Grīnbergs**.

O ano de nascimento de **Mikhail Voronets** foi fixado em **1902**. A continuidade de **Artūrs Graudiņš** foi corrigida: preso em 1940, escapa de um transporte durante a retirada soviética de 1941 e foge para o oeste em 1944.

## Correção de estilo

A regra `regras/estilo-historico.md` passou a ser obrigatória. A segunda edição remove metanarração de worldbuilding, slogans autorais, explicações ao leitor e fórmulas repetidas como “menos X, mais Y”. Os arquivos históricos devem registrar acontecimentos e consequências materiais; justificativas editoriais ficam fora da cronologia.

## Estado da revisão

- [x] Demografia de 1954–1979 refeita.
- [x] 1920–1939 tornado politicamente e socialmente menos limpo.
- [x] 1940 como República da União melhor fundamentado.
- [x] Resistência e repressão de 1944–1953 ampliadas.
- [x] Transferências territoriais reescritas com mecanismos soviéticos.
- [x] Repressão de 1960–1979 variada com casos severos selecionados.
- [x] Nomes e termos artificiais revistos.
- [x] Metanarração e vícios de linguagem removidos dos blocos históricos revisados.
- [x] Todos os blocos `historia/`, `resumos/` e `personagens/` até 1979 atualizados.

A base de 1920–1979 está editorialmente consolidada para a continuação da cronologia.