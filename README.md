drag this into your bookmarks bar

[cyberanswer](javascript:(function()%7Bvar%20answer%20%3D%20prompt(%22What's%20the%20CyberAIO%20answer%3F%22%2C%20%22%22)%3Bvar%20link%20%3D%20'https%3A%2F%2Fcybersole.io%2Fapi%2Fshop%2Fpurchase%3Fanswer%3D'%3Bvar%20full%20%3D%20link.concat(answer)%3Bvar%20xmlhttp%20%3D%20new%20XMLHttpRequest()%3Bxmlhttp.onreadystatechange%20%3D%20function()%20%7Bif%20(this.readyState%20%3D%3D%204%20%26%26%20this.status%20%3D%3D%20200)%20%7Bvar%20myObj%20%3D%20JSON.parse(this.responseText)%3Bif%20(myObj.url%20%3D%3D%20undefined)%20%7Balert(%22Wrong%20answer%22)%7D%20else%20%7Bwindow.location%20%3D%20myObj.url%3B%7D%7D%7D%3Bxmlhttp.open(%22GET%22%2C%20full%2C%20true)%3Bxmlhttp.send()%7D)())


make sure youre on cybersole.io/api/shop/purchase

-dogman for amnotify
