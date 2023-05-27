# tec-actions

Esta acción permite el deploy en servidores on premise

## Uso
 
```yml

- uses: actions/checkout@v3
  with:
    # IP privada VPN asignada a Github
    # Default: ''
    HOST_IP_VPN_WIREGURD_GITHUB: ''

    # Llave privada asignada a la VPN de Github
    # Default: ''
    WIREGUARD_PRIVATE_KEY_GITHUB: ''

    # Llave publica VPN del servior Endpoint
    # Default: ''
    WIREGUARD_PUBLIC_KEY_ENDPOINT: ''

    # Cadena de IPs permitidad
    # Default: ''
    WIREGUARD_ALLOWED_IPS: ''

    # IP publica y puerto para la conexion a la VPN del Endpoint
    # Default: ''
    PUBLIC_IP_AND_PORT_VPN_ENDPOINT: ''
 

```
