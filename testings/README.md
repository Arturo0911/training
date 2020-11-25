

# SUBNETEO PROTOCOLO RIP V1
    
    - Realizamos todo el esquema de la topología en cisco.
    - Después asignamos a cada router su respectiva ip mediante los comandos
        
        * enable.
        * configure terminal.
        * interface fastEthernet (solo es dar un TAB y automáticamente se te autocompleta el comando) adicional el serial del puerto fastEthernet.
        * ip address (la dirección ip y su respectiva máscara de subred).
        * no shutdown para que se guarden los cambios.
        * Luego en el mismo router si está conectado por DCE a otro router, debemos asignarle su ip de conección 
            mediante interface serial (numero serial)
            luego ip address (dirección ip y su respectiva máscara)
        * Agreagmos network la red en la que estamos, luego network a cada red por que voy a pasar es decir las rutas de la red.

    - Escriba el comando banner motd # Escriba aquí el mensaje del día # .
