# O que é Copy-on-Write(COW)

É um conceito essencial para entender as camadas de um container no Docker. Significa que um recurso só é alocado quando é modificado.

Um container é formado por N camadas read-only e a última camada(superior) read-write.
