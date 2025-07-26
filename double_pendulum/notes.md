# Notes on 3D Printed Double Pendulum

This part of the project focused on creating a physical **double pendulum**, a well-known example of a chaotic system. The double pendulum exhibits highly sensitive dependence on initial conditions, making it ideal for demonstrating chaos in motion.

## Design Overview

The model consists of three main 3D printed parts:

- `First Arm.stl` – The upper segment of the pendulum  
- `Second Arm.stl` – The lower segment, connected to the first arm  
- `Shoulder.stl` – A mounting piece to attach the pendulum to a wall or vertical surface  

I designed these parts in **Fusion 360**, and have also included the original `.f3d` files for future editing or customization.

### Assembly

- The joints were connected using **R6-2RS ball bearings**:  
  - **Inner Diameter:** 3/8"  
  - **Outer Diameter:** 7/8"  
  - **Width:** 9/32"

These bearings allowed for smooth, low-friction rotation necessary for clean, unpredictable motion.

## Mounting Considerations

The shoulder mount is intended to be secured to a **wall or vertical surface**.  
⚠️ **Important:** Ensure there's a slight **gap between the wall and the mounted print.**  
If the pendulum hangs too close to the surface, the arms may hit the wall during motion, which disrupts the demonstration of chaotic behavior.

Solutions:
- Use spacers, washers, or a mounting bracket to offset the shoulder from the surface.
- Test clearance before full assembly.

## Performance

Once correctly mounted and aligned, the double pendulum performed as expected, showing erratic and non-repeating motion patterns.

The included demo video shows **four double pendulums released simultaneously** from nearly identical positions. Despite their similarities, each one quickly diverges into a unique path—visually demonstrating the principle of **sensitive dependence on initial conditions**.

## Attached Files

- `First Arm.stl`  
- `Second Arm.stl`  
- `Shoulder.stl`  
- `First Arm.f3d`  
- `Second Arm.f3d`  
- `Shoulder.f3d`  
- `dp_print.jpg` – Assembled model photo  
- `dp_demo_video.mp4` – Synchronized release of four pendulums  
