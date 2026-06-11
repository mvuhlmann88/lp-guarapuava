# assets/img — Imagens necessárias

## Obrigatórias

| Arquivo           | Uso                          | Dimensão recomendada | Observações                                      |
|-------------------|------------------------------|----------------------|--------------------------------------------------|
| hero-bg.jpg       | Fundo da seção hero          | 1920×1080px          | Foto aérea de SFS / litoral / cidade. JPG comprimido ~200-400kb |
| logo-white.svg    | Logo no header (fundo escuro)| —                    | Versão branca do logo Palmasnet                  |
| logo-blue.svg     | Logo no header (fundo branco)| —                    | Versão colorida / azul do logo Palmasnet         |
| logo-footer.svg   | Rodapé                       | —                    | Pode ser a mesma versão branca                   |

## Recomendadas (melhoram conversão)

| Arquivo           | Uso                          | Dimensão recomendada | Observações                                      |
|-------------------|------------------------------|----------------------|--------------------------------------------------|
| foto-ju.jpg       | Avatar do depoimento da Ju   | 80×80px              | Foto do cliente (opcional — tem fallback com iniciais) |
| foto-jose.jpg     | Avatar do José Renato        | 80×80px              | Idem                                             |
| foto-mariana.jpg  | Avatar da Mariana            | 80×80px              | Idem                                             |
| foto-andreia.jpg  | Avatar da Andreia            | 80×80px              | Idem                                             |

## Como substituir as imagens

Todos os caminhos de imagem no index.html estão em `assets/img/`.
Substitua os arquivos mantendo os mesmos nomes, ou edite os atributos `src` no HTML.

## Hero background sem foto

Se não tiver foto disponível ainda, o CSS já tem um fallback de cor sólida (azul escuro).
A LP funciona sem a hero-bg.jpg — a foto melhora mas não quebra o layout.
