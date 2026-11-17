# Betty Barbearia

Agendamento online (Spring Boot + Gradle, Java 21).

## Como abrir (IntelliJ)
1. File > Open > escolha a pasta `betty` (a que tem o `build.gradle`).
2. Project SDK = Java 21. Em Settings > Build Tools > Gradle, "Gradle JVM" = Java 21.
3. Clique em "Load" na notificação do Gradle e espere terminar.
4. Abra `BettyApplication.java` e clique no play verde ao lado do `main`.
5. Navegador: http://localhost:8080 (cliente) e http://localhost:8080/painel (equipe).

## Logins de teste (TROQUE antes de publicar)
| Usuário | Senha | Acesso |
|---|---|---|
| dono | dono123 | agenda de todos, equipe, serviços |
| carlos / rafael / joao | carlos123 / rafael123 / joao123 | só a própria agenda |

Os dados ficam em memória: ao reiniciar o app, voltam ao padrão.
