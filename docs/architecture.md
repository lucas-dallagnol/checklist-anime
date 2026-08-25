erDiagram
<br>
 USUARIO ||--o{ CHECKLIST : possui
 ANIME ||--o{ CHECKLIST : esta_em
 USUARIO { 
string id PK
 string nome
 string email
 string senha
 } 
ANIME { 
string id PK 
string titulo
 string gênero
 int total_episodios
 string imagem
 } 
CHECKLIST {
 string id PK 
string usuario_id FK
 string anime_id FK
 string status
 int episodio_atual
 }
