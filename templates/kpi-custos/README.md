# Templates HTML de KPI de Custos para Power BI Desktop

Dois cartões prontos para serem utilizados com visuais que renderizam HTML no Power BI (ex.: HTML Content, DAX HTML ou Deneb com Markdown). Basta substituir os valores de exemplo pelos campos ou medidas do seu modelo.

## Como usar
1. Copie o conteúdo de um dos arquivos `.html`.
2. Troque os textos de exemplo pelos seus campos do Power BI (por exemplo, use medidas formatadas em DAX via `VALUE()` ou `FORMAT()` dentro do HTML).
3. Se o visual aceitar parâmetros dinâmicos, altere as porcentagens das barras (`width`) e os números dos elementos `id` (`valor-principal`, `meta`, `atingimento`, `delta`, `fonte`, `ticket`) com as medidas do relatório.
4. Cole o HTML final no visual escolhido.

### Dicas rápidas
- Mantenha os símbolos (ex.: `▼` ou `▲`) para indicar direção e altere a classe `negative` em `.delta` quando a variação for desfavorável.
- Ajuste a largura dos cartões via CSS (`width`) para caber em diferentes layouts do dashboard.

## Arquivos disponíveis
- `cartao-custo-essencial.html`: cartão com foco em valor total, meta, atingimento e variação mensal, com progress bar.
- `cartao-custo-compacto.html`: versão mais compacta para custo operacional, destacando YoY e ticket médio.
