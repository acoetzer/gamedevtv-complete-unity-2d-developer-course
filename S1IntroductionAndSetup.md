<!-- Section Number-->
<h2>SECTION 1</h2>

<div align="center">
    <!-- Course Full Name & Link to Specific Course -->
    <h3>
        <a href="https://www.gamedev.tv/courses/unity-complete-2d" alt="Link to the related GameDev.tv course" target="_blank">COMPLETE UNITY 2D DEVELOPER: CREATE YOUR OWN 2D GAMES USING UNITY C#</a>
    </h3>
    <!-- Section Heading -->
    <h4>
        INTRODUCTION & SETUP
    </h4>
    <br>
</div>

In this section, we learned how to download and set up both [Unity](https://unity.com/ 'Link to Unity Website') and [Visual Studio Code](https://code.visualstudio.com/ 'Link to Microsoft Visual Studio Code'). This process included configuring Unity's preferences to use Visual Studio Code as the primary code editor.

Within Unity, we explored the various sections of the interface and how to reset the interface back to default within the `window > layouts` tab. Looking the Inspector pane, this is where we learned about different components and how to view and manipulate various properties such as the X, Y, Z coordinates, the color of sprites, and the Z index (or order in layer) property, which determines whether an object appears above or below another object.

<details>
    <summary>Inspector Menu Image</summary>
    <br>
    <img src="./assets/images/S1/InspectorTab.png" alt="" width="100%">
</details>

<br>

We also explored the Hierarchy pane, which displays various objects in the scene, such as the camera and sprites. Additionally, we learned how to add objects to the scene by right-clicking in the Hierarchy, selecting **2D Object**, then **Sprites**, and choosing the desired shape.

<details>
    <summary>Hierarchy Menu Image</summary>
    <br>
    <img src="./assets/images/S1/HierarchyMenu.gif" alt="" width="100%">
</details>

<br>

#### 💡**Note:** What is a Sprite?
> *Sprites are 2D images or animations used in game development and other graphical applications. They are typically used to represent characters, objects, UI elements, and backgrounds in a 2D game. In the context of Unity and other game engines, sprites are a fundamental building block for creating visually rich, interactive experiences.*

We then learned about the controls and how we can manipulate the sprites on the stage using both the interface and keyboard shortcuts as well as panning around the scene. The keyboard shortcuts do the following:

<details>
    <summary>Tools Menu Interface</summary>
    <br>
    <img src="./assets/images/S1/ToolTab.png" alt="" width="10%">
</details>
<br>
<details>
    <summary><strong>W</strong> Move Tool, Moves the Object.</summary>
    <br>
    <img src="./assets/images/S1/MoveTool.png" alt="" width="20%">
</details>
<br>
<details>
    <summary><strong>E</strong> Rotate Tool, Rotates the object.</summary>
    <br>
    <img src="./assets/images/S1/RotateTool.png" alt="" width="20%">
</details>
<br>
<details>
    <summary><strong>R</strong> Scale Tool, Scales the Object.</summary>
    <br>
    <img src="./assets/images/S1/ScaleTool.png" alt="" width="20%">
</details>
<br>
<details>
    <summary><strong>T</strong> Rect Tool, Is like free-transform</summary>
    <br>
    <img src="./assets/images/S1/TransformTool.png" alt="" width="20%">
</details>

<br>

Shortly after, we were challenged to make a pretend platformer scene with the information we just learn't on how to create & manipulate sprites.

<details>
    <summary>Create a Pretend Platformer Scene Challenge</summary>
    <br>
    <img src="./assets/images/S1/ChallengeScene.png" alt="" width="100%">
</details>

<br>

We then dived into creating a C# Script file with the code `Debug.Log("...")` and then how to run the Unity game and seeing what message is printed to the console. The way we made the script file was by right clicking inside the project asset pane and selecting `Create > C# Script`.

<details>
    <summary>Creating a C# Script File</summary>
    <br>
    <img src="./assets/images/S1/MakingAScriptFileInUnity.gif" alt="" width="100%">
</details>

<br>

Finally, we also installed Visual Studio Code Extensions (C#, Unity Code Snippets).