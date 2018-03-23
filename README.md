# JOB

Um job é uma tarefa que o Jenkins deve fazer. Normalmente, tem alguns parâmetros de execução, juntamente com alguns procedimentos que podem ser feitos antes ou depois de sua execução. Por exemplo, um job de build de uma aplicação web, ou job de execução de um conjunto de testes. O mesmo job normalmente tem um ou mais builds.

# Build

É a construção, uma execução de um job (tarefa), por exemplo o procedimento de montar um pacote, que pode envolver download, compilação ou testes. O build pode ser considerado como uma instância de um job, como o último processo de um job de deploy. Ele também possui diferentes status:

1. Falha no Build (RED)
2. Build Instavel (YELLOW)
3. Build Feito Com Sucesso (BLUE)
5. Build Pendente (GRAY)
6. Build Cancelado (GRAY)
7. Build Desligado (GRAY)
