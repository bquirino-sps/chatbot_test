# @FaztNoteChatBot

## Chatbot de notas

Este es un Bot que te ayuda a guardar notas. Puedes guardas las notas que quieras u organizarlas dentro de varios blogs. Además puedes consultarlas cuando quieras.

This is a Bot that help you to save notes easy, You can save the notes you want or organize them inside various blogs. Also you can check them when you want.
About: Bot para guardar notas rápido. 

## Commands

- start \- Inicia el bot.
- help \- Muestra información detallada sobre los comandos.
- simplenote \- \<note\> Escribe una nueva nota con la fecha actual.
- newnotemedia \- \<note\>(Opcional) Escribe una nota con la fecha actual y el archivo por ser enviado en un segundo mensaje.
- newblognote \- \<blog\> ; \<note\>Escribe una nota en un blog especifico, el blog es creado si no existe.
- newblog \- \<blog\> Crea un nuevo blog de notas.
- newblognotemedia \- \<blog\> ; \<note\>(Opcional) Escribe una nota en blog especifico con el archivo por ser enviado en un segundo mensaje.
- shownotesfromblog \- \<blog\> Obtiene las notas de un blog especifico.
- keyboard \- Muestra el teclado.


## Dependencies

- datetime
- requests
- sys
- sqlite3
- telebot
- threading (future)
- time
- uuid
