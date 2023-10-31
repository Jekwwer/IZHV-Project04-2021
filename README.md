# IZHV-Exercise04-2021

Solution for the 4th assignment from the course _'[IZHV (Introduction to Game Development)](https://www.fit.vut.cz/study/course/250838/)'_ for the academic year 2021/22 at VUT FIT. \
Řešení 4. úkolu z předmětu _'[IZHV (Základy herního vývoje)](https://www.fit.vut.cz/study/course/250838/.cs)'_ pro akademický rok 2021/22 na VUT FIT.

## Task: Materials and Effects

[Full Assignment Description](http://cphoto.fit.vutbr.cz/ludo/courses/izhv/exercises/e4/)

**1. Setup:**

- Download the project template from the Materials section.
- Ensure Blender is installed for .blend file compatibility.
- Open the project in Unity in 3D editor mode and run it to check the default kitchen scene.

**2. Using Unity Materials:**

- **Broken Sink:**
  - Locate the sink in the scene.
  - Navigate to `Assets/Materials/Kitchen`.
  - Create a new material named "Sink".
  - Configure the shader to "Universal Render Pipeline/Lit".
  - Adjust material parameters to resemble steel.
  - Apply the "Sink" material to the sink in the scene.

**3. Shader Graph and Procedural Wood:**

- **Boring Table Fix:**
  - Navigate to `Assets -> Shaders -> Kitchen`.
  - Create a new Shader Graph named "SimpleWoodSG".
  - Open the Shader Graph editor.
  - Add a color property named "BaseColor" with a brown default value.
  - Connect the "BaseColor" property to the Base Color input of the Fragment node.
- **Table Wood Gradient Noise:**
  - Add nodes for Gradient Noise and Multiply.
  - Configure them as shown in your description.
- **Custom Function Node for Wood Contour:**
  - Add a Custom Function node.
  - Configure inputs, outputs, and code as given in the description.
  - Connect nodes to create a pattern reminiscent of wood grain.
- **Complete the Wood Material:**
  - Use the created Shader Graph to produce materials for the table top ("TableTop") and table legs ("TableLeg").
  - Assign these materials to the appropriate elements of the table in the scene.

**4. Personalizing the Kitchen:**

- Navigate to `Assets -> Materials -> Kitchen`.
- Choose at least 3 materials.
- For each selected material:
  - Create a Shader Graph that represents its visual and physical properties.
  - Experiment with different nodes and configurations in Shader Graph to achieve desired effects.
- Apply the customized materials to the corresponding objects in the kitchen scene.
- Be creative and explore different looks, textures, and effects.

## Result

TBD

## Evaluation

Total points: **6/6**
