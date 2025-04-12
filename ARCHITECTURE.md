
```
chat-app/
├── backend/
│   └── src/
│       ├── main/
│       │   ├── java/com/chatapp/
│       │   │   ├── controller/         ← WebSocket & REST endpoints
│       │   │   ├── model/              ← Entidades como Message.java
│       │   │   ├── service/            ← Lógica de chat (ex: broadcast)
│       │   │   └── ChatAppApplication.java
│       │   └── resources/
│       │       ├── static/             ← Frontend HTML, CSS, JS
│       │       └── application.properties
├── frontend/                            ← Apenas durante desenvolvimento
│   ├── index.html
│   ├── style.css
│   └── chat.js
├── pom.xml
```