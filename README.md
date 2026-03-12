# meusite
Site 
html = [[
<!DOCTYPE html>
<html>
<head>
<title>Meu Site</title>
</head>

<body>
<h1>Meu primeiro site</h1>
<p>Site criado usando Lua!</p>
</body>

</html>
]]

file = io.open("site.html", "w")
file:write(html)
file:close()

print("Site criado!")