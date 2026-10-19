# Documento de design — USLORDS One Line

## Conceito

RPG de ação e plataformas 2D com exploração livre, zonas revisitáveis, narrativa e evolução das personagens. As referências a Super Mario e RPGs orientam mecânicas, não a cópia de conteúdo.

## Visual (regra principal)

- Bonecos desenhados com linhas limpas, sem mãos nem pés.
- Animações suaves de pernas, braços e corpo ao andar, correr e saltar.
- Mundo com contornos simples em fundo claro e diálogos legíveis.
- TNT: caixa TNT como cabeça, pavio, casaco com capuz (a melhorar visualmente no protótipo), nunca descalço na versão canónica do universo; o estilo sem pés visíveis é uma simplificação artística.
- Aeris: flor no cabelo, vestido e cura; Mask: máscara e identidade própria.

## Regras da progressão

- TNT começa no nível 1, com 3 corações e 10 Mking.
- Inimigos derrotados concedem XP e Mking.
- Subir de nível aumenta os corações máximos (taxa exata sujeita a equilíbrio).
- O nível dos inimigos é mostrado acima da cabeça, com cor relativa ao nível do TNT.
- Inimigos **comuns reaparecem** quando se revisita uma região e podem voltar a conceder XP/Mking.
- **Chefes e inimigos especiais não reaparecem** após serem derrotados; o progresso fica guardado.
- É possível regressar às zonas visitadas para explorar, recolher itens e cumprir missões.

## Sistemas

- Inventário com armas, poções, equipamentos e habilidades.
- Cinco atalhos configuráveis (teclas 1–5).
- Guardar e carregar progresso em três espaços.
- Pausa, menu principal, diálogos e exploração sem tempo limite.

## História e mundo

A demo situa-se em Speranzu, na Nação Men, no universo USLORDS, com TNT, Aeris e Mask. O enredo completo deve respeitar o livro e cânone do criador.

## Próximas prioridades

1. Testar a versão publicada no browser e corrigir bugs de jogo.
2. Melhorar animações de todos os personagens e expressões de combate.
3. Separar HTML, CSS e JavaScript em ficheiros de fácil manutenção.
4. Criar modelo de dados de equipamentos, raridade, comércio, missões e chefes persistentes.
5. Evoluir a exploração, acessibilidade e equilíbrio de combate.

## Nota de gravações

Os saves atuais usam armazenamento local do browser; mudar de dispositivo, apagar dados do site ou usar origem diferente pode impedir a recuperação. Futuramente: exportação/importação de gravações.
