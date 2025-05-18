# InnovateHealth - 3D Digital Product Abstraction Layers Visualization

This project is a 3D interactive visualization demonstrating the abstraction layers of rule-based entities, using a hypothetical US digital health company, "InnovateHealth," and its AI-powered wellness monitoring app, "WellTrack," as a use case. The visualization aims to represent how different layers of rules and assessments apply to a digital product, incorporating various architectural dimensions.

This 3D representation serves as a prototype to visualize concepts from the articles:
* AI Rule-Based Entities: Abstraction, Evaluation, AGI/ASI Futures ([https://datatunnel.io/ai-rule-based-entities-abstraction-evaluation-agi-asi-futures/](https://datatunnel.io/ai-rule-based-entities-abstraction-evaluation-agi-asi-futures/))
* ACI Architecture Evaluation Methodology ([https://datatunnel.io/aci-architecture-evaluation-methodology/](https://datatunnel.io/aci-architecture-evaluation-methodology/))

## Features

* **Interactive 3D Scene:** Visualizes different abstraction layers as distinct 3D shapes (Tori, Cylinders, and grouped components).
* **Detailed Information Display:** Clicking on a 3D layer or its corresponding legend item reveals detailed information about its "Rules" and "Assessment" in a side panel.
* **Dynamic Highlighting & Animation:** Selected layers are highlighted and subtly animated for better visual feedback.
* **Legend for Layers:** A clear legend lists all the visualized layers, their names, and color codes, and also allows for interaction.
* **Responsive Layout:** The interface elements adjust to different screen sizes.
* **Visual Representation of Connections:** Lines connect components of the "Application/System Architecture Layer" to the "Technology Architecture Layer".

## Abstraction Layers Visualized

The visualization includes the following layers for "InnovateHealth" and its product "WellTrack":

1.  **Global/National Legal & Regulatory Layer**
2.  **State/Local Regulatory Layer**
3.  **Industry Standards Layer**
4.  **Corporate Governance & Strategy Layer (InnovateHealth)**
5.  **Business Unit/Product Line Layer**
6.  **Digital Product Layer (WellTrack)**
7.  **Application/System Architecture Layer** (represented by multiple components labeled Cx)
8.  **Technology Architecture Layer**
9.  **Data Architecture Layer**

## How to View

1.  Clone this repository or download the `3d-rule-based-entities-use-case-innovatehealth.html` file.
2.  Open the `3d-rule-based-entities-use-case-innovatehealth.html` file in a modern web browser that supports WebGL (e.g., Chrome, Firefox, Edge, Safari).

## Technologies Used

* **HTML5**
* **CSS3** (with Tailwind CSS for styling some elements and custom styles for the neon theme and layout)
* **JavaScript**
* **Three.js (r128):** For creating and rendering the 3D graphics.
* **Google Fonts (Inter):** For typography.

## Development

The core logic for the 3D scene, interactions, and data display is contained within the `<script>` tags in the HTML file.

* **Scene Setup:** Initializes the Three.js scene, camera, renderer, and lighting.
* **Object Creation:** Dynamically creates 3D objects (Torus, Cylinder, AppComponents) based on the `layersData` array. Each object stores its relevant rules and assessment information.
* **Interaction:** Uses raycasting to detect clicks on 3D objects.
* **Information Panel:** Displays details of the selected layer.
* **Legend:** Dynamically generates an HTML legend that also allows for layer selection.
* **Styling:** Employs a neon-on-black theme with distinct colors for different layers and UI elements.

## Credits

* The concept and data for this visualization are based on the InnovateHealth use case.
* The prototype was built using Gemini 2.5 Pro (preview), as stated in the HTML file's footer.
