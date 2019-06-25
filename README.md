# gb_robots
Configura la variable de entorno GAZEBO_MODEL_PATH para indicar que los modelos de Gazebo se carguen desde el directorio 'models' del propio paquete. Para ello, incluye la siguiente línea en tu .bashrc:

export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:~/your_workspace_name/src/gb_robots/worlds/models
