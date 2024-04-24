### Estudando Kotlin e fazendo uma lista de compras

-Mapa mental: View -> ItemData -> Adapter <- Layout 
                                    |
                                RecycleView

Adapter vai ser o responsavel por gerenciar a criação da lista, a exibição dos itens e também vai ser responsavel por definir o layout que vai será utilizado nos itens.
A função do adapter vai ser abstrair todas as funções da lista, sendo assim, o adapter não precisa saber os detalhes dos seus itens, ele precisa apenas ser um facilitador.

Todo o RecycleView precisa de um objeto chamado "ViewHolder"
ViewHolder é responsavel por manipular o conteudo visual de um item da lista e guardar uma instancia daquele item.
