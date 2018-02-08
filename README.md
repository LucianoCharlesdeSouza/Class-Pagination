# Class-Pagination
Classe de paginação

# Métodos publicos

# MaxPerPage($max)
<p>Método que recebe o valor máximo de registros por página</p>

# Page($name_page)
<p>Método que recebe o nome do page <strong>Ex: </strong>/usuarios?<strong>pagina</strong></p>

# MaxLinks($maxlinks)
<p>Método que recebe o valor máximo de links visiveis a esquerda e a direita da paginação</p>

# Places(array $places_values)
<p>Método que recebe um array para usar como substitutos no Bind</p>

# CreatePagination($Query)
<p>Método que recebe uma string SQL para retornar os itens para a paginação</p>

# CreateLinks()
<p>Método que gera os links de paginação</p>
