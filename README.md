# Playbook para la Raspberry

## Modo de Uso

1. En el archivo `inventario.txt`, especifica las direcciones IP de las máquinas a las que deseas aplicar el playbook.

2. Ejecuta el siguiente comando en tu terminal:

   ```bash
   ansible-playbook -i inventario.txt raspcasaplaybook.yml

---------------
En caso de usar otro usuario diferente a pi

ansible_user: pi  # Usuario que ejecutará el playbook

Cambiar la variable dentro de inventario.txt.