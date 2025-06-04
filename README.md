# Laboratorios-del-modulo-II- Practica 1 COMANDOS
🔁 Actualización del sistema y manejo de repositorios

    sudo yum update -y
    → Actualiza todos los paquetes del sistema automáticamente.

    sudo yum repolist allA
    → Muestra todos los repositorios configurados (activos e inactivos).

    sudo yum repolist nfv
    → Muestra información del repositorio nfv si está disponible.

🔍 Buscar e instalar paquetes

    sudo yum search bashtop
    → Busca el paquete bashtop en los repositorios disponibles.

    sudo yum install epel-release -y
    → Instala el repositorio EPEL, necesario para acceder a paquetes como bashtop.

    sudo yum install bashtop -y
    → Instala el monitor de sistema bashtop automáticamente.

🧹 Eliminar paquetes y limpieza

    sudo yum remove bashtop -y
    → Elimina el paquete bashtop.

    sudo yum autoremove -y
    → Elimina dependencias que ya no se utilizan.

🗑️ Eliminar configuración de usuario

    sudo rm -rf ./.config/bashtop
    → Borra la carpeta de configuración de bashtop del usuario actual.
