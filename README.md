# **Instalación de Voyager sobre Laravel y configuración del sitio web y su administración.**

- Creamos el proyecto de Laravel desde la terminal de Laragon.

- Metemos los comandos npm install y npm run dev.

- Instalamos Voyager sobre el proyecto con los siguientes comandos:

  1. composer require tcg/voyager

  2. php artisan voyager:install --with-dummy

     ![img](https://lh5.googleusercontent.com/ObLKCdYmWFgbv2Rz6jUcSVWLNelMYk7qv9NB1tRXkyQlKslPxj0oz90l2INzKkoWXa7WiagyNvuwzzbvqnZY3O-Y2DqBJRDwKdsFGUUmw1UjlvjsrwePg9dm4gBUo4oWhn_GAdS3vXNSN88-8w)

     

     - Los datos para iniciar sesión en la aplicación serán: 

       - **email:** admin@admin.com 

       - **password:** password

         

     - La aplicación se verá de la siguiente manera en este paso: 

       

       ![img](https://lh4.googleusercontent.com/6VAVHjzbOXFi3mvMz9PHXQSFDWZjNkgDWjhISS87pKns44NY20OASUNnbNsnKQnUX8p6X155p-KV_gciEGyTlNeVyTdF3aA95EvhiHN3v0f4T7SO3SXZ2vMKijjZiPAeuXmkiqiD7nQk4H_jXA)

       

       - En el caso de esta aplicación las imágenes de gestión de usuarios, posts, y de la propia web se almacenarán en public/storage:

         ![img](https://lh6.googleusercontent.com/Jn-mK7eaqveWDf5xbzvOBxt-gNMX-2dmjBcCEt5159JBiIObNGwwo2cG-3D5VdkJ902Wugvel9CHLN36C7acmj6E5gaWGXrKsjs8_cy9YKpigixU15BgQaq3zpzvr8am-0p6IoHw7NQEZV7UtQ)



- Desde la propia aplicación podremos editar tanto los post como las imágenes asociadas.

  

  ![img](https://lh5.googleusercontent.com/hTyAEJPc1ihngFU1p5c0aF1iiNA1AIFo0v2Xeru6VPwPI4KCEm2MfzMqNReqTm1SsW0rqsW_BNJImQgDSowN83Aa714Edo6HHLTzHH7Jn9VsoYFqlXYT93OSlICaSJKA23PrhWym_XwYy4O-QA)

  

  - A continuación crearemos un nuevo menú a parte del principal para el admin.

  

  ![img](https://lh3.googleusercontent.com/yV2jTerZI99qjt4ceAeTDIb6nQiACaUVcCyCEeBnSYG4DrEhX5ts9-5NVMqA8e2wQNs1G23-AUiEWZHGuRLc1mvs1KWciRQzMy039zcIez2HkB28OdMyhOESnYuH6YfqrX1KZ0jJBb-lCQQROg)

  

  - Creamos los apartados que creamos convenientes desde la aplicación, incluimos un CDN de Bootstrap para darle estilos y ya tendremos un menú funcional preparado.

    

    ![img](https://lh4.googleusercontent.com/Hj_L00s-jeFw7ZaryUX1XYMWk8v9bNNYXG3yzF3f8ZC-Ts-WnGrAPtYRd51JQK1RE-aIqEKAgc0BqFbseKZ1mDTPb_ordw6z1M0zq7uLaifurE95nYTHFPt82WCt8R3aTXLCy2QkOpcfpM5MiA)

    

    ![img](https://lh4.googleusercontent.com/kru-__c-D4F2HJ13PS7itNKTffCjjlrVfHbyj9k0bwZuuMx7fCieqFQyBuULnQMOl00Y5wV2L_AWLUP6m64xgCOLfQnrFncomTFtdWY7o2N88TPdO4McaqCM0iFGHJe22ty9FAQTrs_PKH2wrw)

    

    - Voyager también nos permite crear tablas para las bases de datos desde la propia aplicación, personalizarlas a placer y establecer relaciones:

    

    ![img](https://lh4.googleusercontent.com/Qf6-R-Aon2aqZtxeJfZ-T35r8ZMdtFsZ27lOhQVO0zA-2Zg0kt1T72izZajLelLtUhxwWIbeNq2tVeWsxVCQhETrxeWCvMP7pMFloa_QYnY6mwTa7Gw1xrFjIuScQlssQZWfTgvhm0raOieIoA)

    

    ![img](https://lh6.googleusercontent.com/k_ei4eHjTU1o8Z7FZA2GCN0nzPMoHwNW0eqJHyc6aN1rC0ChP38hcVUbhh_Qdv6vSkCRFdAyuJg4-3BD6yVaZct7GCiEgMYYV4kvF0ZbG4l2LZxqj0lDWU2uN5L9az2eTJ6L6wFB7WK6gDr8lw)

    

    - Además, Voyager muestra en la sección Compass muchos de los comandos que puedes ejecutar en la terminal en relación con la aplicación.

      

      ![img](https://lh4.googleusercontent.com/Kb23UgK0BH1OpS82qYaEwgM-05GhzDkiIjdf3qOQqRb5_jY8H78DQ9Oj0mqTcLhpiYQGnLCrlfl1XWm6MGmwXXxWHXxedkuUyt1LU4WKbvje15pBcw0SIaPc05ZCledLDIhzbQnZv09RDRUIBA)