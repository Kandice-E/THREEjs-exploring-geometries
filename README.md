BUILT WITH: Three.js and Vite

GETTING STARTED 
-TO VIEW THE APPLICATION: navigate to this section of my github page: https://kandice-e.github.io/THREEjs-exploring-geometries/.

-TO RUN THE APP LOCALLY:

    -If not already downloaded, download and install Node.js: https://nodejs.org/en. The version used can be found in the package JSON file
    (download and extract project ZIP file).
    -Install the proper three.js version as stated in the package JSON file using the command: npm install --save three.
    -The Vite build tool was used to host the dev server and build the app. This version is also in the package JSON file: https://vite.dev/.
    -Next, from the directory you extracted the ZIP file to, run: npx vite.
    -A local server should be made available for interacting with the application.

SCENE DESCRIPTIONS

-SCENE 1: Basic Mesh Geometries Showcase

    -This scene showcases the following five basic geometries: Plane, Box, Sphere, Cylinder, and Torus.
    -GEOMETRY CONSTRUCTOR PARAMETERS:
        -PLANE (width: 64, height: 16, widthSegments: 10, heightSegments: 5)
        -BOX (width: 5, height: 5, depth: 5, widthSegments: 10, heightSegments: 10, depthSegments: 10)
        -SPHERE (radius: 3, widthSegments: 32, heightSegments: 16, PhiStart: Math.PI / 3, PhiLength: 3 * (Math.PI / 2), thetaStart: 0, thetaLength: Math.PI)
        -CYLINDER (radiusTop: 2, radiusBottom: 2, height: 6, radialSegments: 32, heightSegments: 1, openEnded: false, thetaStart: 0, thetaLength: Math.PI * 2)
        -TORUS (radius: 2, tube: 1, radialSegments: 12, tubularSegments: 48, arc: Math.PI * 2)
![image](https://github.com/user-attachments/assets/27ebb6bb-a8ab-4ef2-b5cc-ecc7fc44459c)


-SCENE 2: Custom Mesh Geometry via BufferGeometry

    -This scene demonstrates the use of the Three.js BufferGeometry to create a custom mesh.
    -The mesh created is a Mobius Strip with wireframe enabled to accentuate the structure.
![image](https://github.com/user-attachments/assets/c277e7f7-5655-404c-a3e0-3a93bd771720)


-SCENE 3: Mesh Modification and Animation

    -This scene modifies two basic meshes from Scene 1 to demonstrate geometry animations and parameter fluctuations.
    -The size and rotation of the cube can be modified using the sliders in the control panel.
    -The sphere rotates on the y-axis at a constant speed. 
![image](https://github.com/user-attachments/assets/6395efcc-d8df-4487-a855-eecca6b101c0)

-SCENE 4: Advanced Materials on Mesh Geometries

    -The final scene showcases three advanced Three.js materials: MeshNormal, MeshDepth, and ShaderMaterial.
    -The Mesh Normal and Mesh Depth are applied to a torus geometry.
    -The ShaderMaterial uses a custom vertex and fragment shader written in GLSL and passed in as a string. A lava texture is sampled and mapped onto a plane geometry where the result simulates a wavy wall of lava on both sides of the plane. 
![image](https://github.com/user-attachments/assets/541b6f3a-eceb-4f38-8458-e212f660c12f)


CONTACT Kandice Estrella March 12th, 2025
