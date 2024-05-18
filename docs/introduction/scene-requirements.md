# Scene Requirement
![Basic Structure Overview](/assets/guides/basic-setup.svg)

Once installed, and to get started with the addon, a given 2D/3D scene will need the below minimum setup:

- A `Camera2D`/`Camera3D` node
- A `PhantomCameraHost` node
  - As a child of the `Camera2D`/`Camera3D`.
- At least one `PhantomCamera2D`/`PhantomCamera3D` node

After this, the scene is now meeting the minimum requirements, where as you move the `PhantomCamera` around the `Camera` is now following it.
