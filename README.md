# Ubisoft UI Effect Add-on

The **Ubisoft UI Effect Add-on** is an extension for **Supertactic UI Effects** and **Supertactic Virtual Cursor** that replicates **Ubisoft-style hover and selection effects**.  
It enhances your UI interactions by providing smooth, responsive visual feedback for buttons and other UI elements.

---

## Features

- Ubisoft-style **hover and selection effects** for UI elements.  
- Smooth integration with **Virtual Cursor** and **UI Effects** packages.  
- Lightweight and easy to integrate into existing projects.  
- Includes a **sample scene** demonstrating usage.  

---

## How to Install

### Using Package Manager (manifest.json)
1. Open your project's `manifest.json` file.  
2. Add the following line inside the `dependencies` section:  

```json
"com.supertactic.ubisoftuieffectaddon": "0.0.3"
````

### Using Package Manager GUI

1. Open **Window > Package Manager** in Unity.
2. Click the **+** icon and select **Add package from git URL...**
3. Enter the Git URL for this package and click **Add**.

---

## How to Use

1. In **Package Manager**, search for **Supertactic UI Effects** and **Supertactic Virtual Cursor**.
2. Import the **Samples** of both packages. Check the **Samples** section.
3. Navigate to the `Samples/UIButtonHoverEffectSample/Prefabs` folder inside the package.
4. Drag and drop the `UIButtonHoverEffect` prefab into your Canvas.
5. Navigate to the `Samples/VirtualCursorSamples/Prefabs` folder inside **Supertactic Virtual Cursor**.
6. Drag and drop the `VirtualCursorManager` prefab into your scene.
7. In the `VirtualCursorManager`, assign your `InputSystem_Actions` to the **PlayerInput** component.
8. Configure your `InputActions_Actions` as needed (keyboard, gamepad, etc.).
9. Drag and drop the `VirtualCursor` prefab into your Canvas.
10. In the `VirtualCursorManager`, under the **Cursor Settings** header, assign the `Cursor Transform` and `Cursor Animator` fields.
11. In the `VirtualCursorManager`, under the **Canvas Settings** header, assign the `Canvas` and `Canvas RectTransform` fields.
12. Run the scene — your UI now has **Ubisoft-style hover and selection effects**!

---

## Samples

This package includes a demo scene to help you get started:

* **Ubisoft UI Effect Sample**
  A scene demonstrating the hover and selection effects in action on buttons.

To import it:

1. Go to **Window > Package Manager**.
2. Select **Ubisoft UI Effect Add-on**.
3. Expand the **Samples** section and click **Import**.

---

## License

This project is licensed under the **Supertactic License**.  
See the [LICENSE](LICENSE) file for details.  