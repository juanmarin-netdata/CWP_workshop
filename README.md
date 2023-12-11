# Scripts de Configuración de Clúster Kubernetes

Este repositorio contiene scripts Bash para configurar un clúster Kubernetes, ideal para la automatización y gestión de aplicaciones en contenedores.

## Scripts

1. `init_cluster.sh`: Inicializa un clúster Kubernetes, configura `kubectl`, instala Calico y verifica los nodos.
2. `install_kubernetes.sh`: Prepara el sistema para Kubernetes, instala componentes clave y previene actualizaciones automáticas.
3. `setup_containerd.sh`: Configura Containerd con ajustes de kernel y red para Kubernetes.

## Uso

Sigue estos pasos:
1. Ejecuta `setup_containerd.sh`.
2. Ejecuta `install_kubernetes.sh`.
3. Ejecuta `init_cluster.sh`.

## Prerrequisitos

- **Sistema Operativo**: Linux.
- **Conocimientos**: Administración de sistemas Linux y contenedores.
- **Herramientas**: `curl`, `sudo`, terminal.
- **Red**: Conexión a internet.
- **Permisos**: Privilegios de superusuario o `sudo`.
- **Hardware**: Al menos dos servidores, uno para el Control Plane y otro como Worker Node.

## Notas Adicionales

- **Kubernetes**: Orquestador de contenedores para la administración de aplicaciones.
- **Containerd**: Plataforma de ejecución de contenedores.

Consulta los comentarios en cada script para más detalles.


