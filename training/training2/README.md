# STEPS TO SETTINGS CISCO PACKET TRACER.



    - disable dns searching: after configure terminal type "no ip domain-lookup" and press enter and "exit"
        to check if this step was successfully because don't watch any message; type after prompt  Router# "show run | include domain-lookup" and press enter
        you must to see "no ip domain-lookup".

    - Message to the day (MOTD) type: "banner motd #" press enter   <message> and close with #
    - Console password : Router(config)# line console 0 press enter
        Router(config-line)# password <your password>
        Router(config-line)# login (enable password)
        Router(config-line)# exit
        Router(config)#
    - RouterPruebas> enable
        Router# config terminal
        Router(config)# line vty 0 4 (create the 5 lines VTY, but couldn't be one e.g vty 0 crea las 5 líneas VTY, pero podría ser una sola. Ej: line vty 0)
        Router(config-line)# password <your password> (contraseña para las 5 líneas en este caso)
        Router(config-line)# login (enable password)
        Router(config-line)# exit
        Router(config)#
