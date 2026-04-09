# 3D Collision (Xogot 3D Tutorial)

This project contains the example scenes and assets used in the 
**Xogot 3D Modular Series – Introduction to 3D Collisions** tutorial by **Erin Uptegrove**.

It demonstrates how collision works in **Xogot** — the iPad and iPhone port of
the Godot Engine — including how to configure colliders, choose the right
collision shape, and control interactions using layers and masks.

The project includes sample scenes showing different collider types, collision
setups, and how objects interact in a 3D environment.

---

## Features

* Add and configure **CollisionShape3D** nodes for physics bodies  
* Compare collider types: **Trimesh (concave)**, **Convex**, and standard shapes  
* Automatically generate colliders from meshes and CSG  
* Create colliders manually for custom setups  
* Use multiple colliders to approximate complex shapes  
* Understand performance tradeoffs between accuracy and speed  
* Configure **collision layers and masks** to control interactions  
* Adjust settings like **margin** and **solver bias**  
* Preview collision behavior directly in example scenes  

---

## Notes

This project focuses on **collision setup and interaction**, not advanced
physics scripting.

Key ideas demonstrated include:

* Colliders are required for physics bodies to interact  
* Simpler shapes are faster and often sufficient  
* Trimesh colliders are accurate but should be used only for static objects  
* Multiple colliders can approximate complex geometry efficiently  
* Collision layers and masks control what interacts in your game  

---

## Video Tutorial

Watch the full walkthrough on the [Xogot YouTube Channel](https://youtube.com/@xogot):

**Introduction to 3D Collisions in Xogot – Game Development in Godot on iPad**  
https://youtu.be/rzo3yKURTOQ

---

## How to Use

1. Download or clone this repository:

   ```bash
   git clone https://github.com/xogot-projects/Xogot-Collision.git