# workspace-publication

ionic start appPublication tabs --type=angular

# Componentes para publicações

ionic g module components/sharedComponents --flat
ionic g component components/publication

# Directivas para manipulação

ionic g module directives/sharedDirectives --flat
ionic g directive directives/HideHeader
ionic g directive directives/StickySegment