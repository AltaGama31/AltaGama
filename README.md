$nomention
$deletecommand 
$author[$nickname $serverNames]
$authorIcon[$userAvatar[$mentioned[1;yes]]]

$thumbnail[$userAvatar[$mentioned[1;yes]]]
$description[
$var[userinfo;$httpGet[https://botdesignerdiscord.com/public/api=$getVar[BOT_TOKEN]&guildID=$guildID&memberid=$mentioned[1]]]

👥 Nombre de usuario 👥
$httpResult[Nombre;...]
$var[userinfo]

🆔 ID del usuario 🆔
$httpResult[ID;...]
$var[userinfo]

👑 ¿Es admin? ⁉️
$httpResult[]
$var[userinfo]

📩 ¿Mensajes directos? 🗒️
$httpResult[mensages]
$var[userinfo]

🤖 ¿Es Bot? 
$httpResult[bot]
$var[userinfo]

🔹 Fecha de creación de cuenta 🔸
$httpResult[cuenta]
$var[userinfo]

📆 Fecha de unión 📆
$httpResult[fecha]
$var[userinfo]

🌃 Días en el servidor 🌃
$httpResult[servidor]
$var[userinfo]

#️⃣ Cantidad de mensajes enviados #️⃣
$httpResult
$var[userinfo]]
$color[FFFFFF]
$footer[$username[$mentioned[1;yes]]]
$footerIcon[$serverIcon]
