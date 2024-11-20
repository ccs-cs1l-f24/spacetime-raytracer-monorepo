Spacetime Softbody Raytracer
=

[THIS PROJECT IS A WORK IN PROGRESS]

This is the monorepo for my spacetime softbody raytracer project :D

Refer to the spacetime-raytracer submodule for the interesting code. The other submodules are my custom forks of a few Rust libraries used by spacetime-raytracer.

Controls: for now, we use WASD to move and P to pause/unpause.

DISCLAIMER: this project *should* work on Windows and MacOS, but it is tested primarily on a Linux machine.

## Build Instructions

To build and run the project, run

```
git clone --recurse-submodules https://github.com/ccs-cs1l-f24/spacetime-raytracer-monorepo.git
cd spacetime-raytracer-monorepo/spacetime-raytracer
cargo run
```

### Dependencies

Required dependencies
- Vulkan
- Rust + Cargo
- A sane window manager

Optional dependencies
- Vulkan SDK / Vulkan validation layers
- shaderc

### Building on MacOS

If you're running MacOS, you will need to have MoltenVK installed for Vulkan to work.

Applications using Vulkan will typically bundle MoltenVK, but I don't have a reference mac to test with.

You can either install it [through brew](https://formulae.brew.sh/formula/molten-vk) or as part of the [Vulkan SDK](https://vulkan.lunarg.com/sdk/home#mac).
