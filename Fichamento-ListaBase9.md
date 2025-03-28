# On Evaluating the Efficiency of Source Code Generated by LLMs

Niu, Changan; Zhang, ting; Li, Chuanyi; Luo, Bin; Lg, Vicent. "On Evaluating the Efficiency of Source Code Generated by LLMs", Apr - 2024. doi: https://ieeexplore.ieee.org/document/10599574

## 1. Fichamento de Conteúdo

O artigo aborda a crescente utilização de modelos de linguagem de grande porte (LLMs) na geração de código e propõe uma avaliação focada na eficiência do código gerado, além da tradicional verificação de correção. Os autores utilizam benchmarks reconhecidos, como HumanEval e MBPP, e realizam uma análise de problemas mais complexos derivados da plataforma LeetCode. O objetivo é identificar como diferentes prompts podem influenciar a qualidade e eficiência da codificação. Os resultados demonstram que, embora a eficiência do código possa ser independente do tamanho do modelo ou da taxa de sucesso, técnicas de prompt mais elaboradas, como o prompting em cadeia de pensamentos, tendem a resultar em códigos mais eficientes, especialmente para problemas complexos. Os achados oferecem insights práticos que podem guiar desenvolvedores na escolha do modelo adequado para suas necessidades

## 2. Fichamento Bibliográfico 

O artigo propõe avaliar a eficiência do código gerado por modelos de linguagem de grande porte (LLMs), destacando que "códigos mais eficientes podem levar a um desempenho mais elevado e eficiência na execução de programas e softwares concluídos por meio de programação assistida por LLMs." (página 1)

A pesquisa utiliza benchmarks como HumanEval e MBPP para medir a correção e eficiência do código gerado pelos LLMs, garantindo "uma análise rigorosa e comparativa." (página 1)

Testes em plataformas como LeetCode são empregados para avaliar problemas de programação mais complexos, permitindo "uma investigação aprofundada sobre a eficiência do código gerado." (página 2)

Vários prompts são explorados para otimizar a geração de código mais eficiente pelos LLMs, e os resultados indicam que "abordagens simples aumentam a eficiência para problemas básicos, enquanto problemas mais complexos se beneficiam de uma abordagem de cadeia de pensamento." (página 3)

O estudo revela que "a eficiência do código gerado por LLMs é independente do desempenho do modelo na geração de código correto," apontando para a necessidade de considerar diferentes estratégias de treino e abordagem de dados. (página 4)

## 3. Fichamento de Citações 

"The efficiency of LLM-generated code is independent of the model's performance on generating correct code and model size."

"Simple prompts enhance efficiency for basic problems, while complex problems benefit from a chain-of-thought prompt."

"For each problem in LeetCodeEval, we first prompt LLMs to generate 3 different C++ codes."

"We use the gem5 CPU simulator, which is the mostly used golden standard in both academia and industry."

"LLMs are considered to have passed the problem if they generate code that passes all test cases."