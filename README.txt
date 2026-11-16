Settlement Studio 8.0
1. Firebase Console: создать проект Spark, добавить Web app, вставить firebaseConfig в firebase-config.js.
2. Authentication: включить Google, добавить домен USERNAME.github.io (заменить USERNAME на свой логин) в Authorized domains.
3. Cloud Firestore: создать базу Standard в production mode.
4. Загрузить index.html и firebase-config.js в корень GitHub Pages. Войти Google. UID можно увидеть в Authentication > Users.
5. Вставить UID в ownerUid в firebase-config.js и вместо REPLACE_WITH_OWNER_UID в firestore.rules. Содержимое rules вставить в Firestore > Rules и Publish. Загрузить обновленный firebase-config.js на GitHub.
6. Открыть сайт, войти, импортировать свой прежний JSON (если есть), нажать Сохранить для всех.
Не публикуйте сервисные ключи или пароли. Конфигурация Web SDK публичная.
