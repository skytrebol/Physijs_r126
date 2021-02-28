# Physijs
 This is a minor update version of "chandlerprall/Physijs"( https://github.com/chandlerprall/Physijs ). Physijs brings a very easy to use interface to the three.js framework. One of the reasons three.js is so popular is because it is so incredibly easy for graphics newbies to get into 3D programming. Physijs takes that philosophy to heart and makes physics simulations just as easy to run.

- Supports three.js r124 
- Supports THREE.BufferGeometry
- Added Vehicle.addWheelMesh()
- Added Vehicle.resetSuspension()
- Added Mesh.setCollisionFlags()

### src_classic: using Classic Worker ####

requires "importScripts" feature, which is currently supported by major browsers such as IE, Edge, Firefox, Chrome, Safari and Opera. 


### src_module: using Module Worker ####
- Supports latest ammo.wasm.js which is used by babylon.js.
- Supports addAction()
- Remove Physijs.scripts.ammo

requires adding "Content-Type: application/wasm wasm" if you want to use ammo.wasm.wasm binary file.

requires "Worker import" feature, which is currently supported by Edge or Chrome. 
https://caniuse.com/?search=import%3A%20Available%20in%20workers
