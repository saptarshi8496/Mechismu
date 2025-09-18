# **Chassis Design & Fabrication – SolidWorks & ANSYS**

This project documents the complete process of design of a rule-compliant chassis for Formula Bharat 2025. The work focused on ensuring driver safety, manufacturability, and compliance with competition rules, while enabling integration with subsystems such as suspension, steering, and powertrain. An inside-to-outside approach was decided upon to design the chassis. This meant that we would start with the design of the powertrain system, such as the battery module, gearbox, motor placement etc. and then work on covering the area as efficiently as possible with the chassis.

## Table of Contents
- Introduction
- Project Workflow
- Key Features
- Softwares Used
- Results and Deliverables

### Material Selection

After careful consideration of the available materials on the basis of strength, cost, availability - we decided upon AISI 4130 (Chromoly Steel) as our material. This provided high strength and lower weight, but at a higher cost. However, it was readily available.

### Preparing the Outer Boundaries and Suspension Points

This was the first step in our design, as having a set 'box' to refer while making changes inside would make the design process simpler.

Three models were prepared - two templates for cockpit opening and cross-section, and one for Percy (95th Percentile Male). The rules regarding the cockpit templates were simple - they had to fit from the opening of the cockpit to a point below the side impact structures (for opening template) and to a point 100mm behind the rear face of brake pedals (for cross-section template). The models were created with dimensionns 10mm larger on each side in order to provide sufficient leeway for small alignment errors in the future.

The Percy model was used extensively to finalise the driver position for our car. In this, proper seat angle and side clearances for the drivers hands were measured and incorporated into the chassis design. This affected the height of the roll hoops and the distance from the front roll hoop to the front bulkhead. The height of the two roll hoops indirectly affected the angle as the top of the driver's helmet must be atleast 50mm from the line joining the top of the roll hoops. Also, the distance affected visibility - making it longer resulted in a more leaned driver.

### Preparing the Suspension Points

The suspension pick-up points were joined to the roll hoops and bulkheads in a star pattern to ensure maximum strength while keeping the design as simple as possible.

### Analysis

Impact analysis were carried out on the chassis to ensure safety. Three tests were performed - Impact (Front, Rear and Side), Bending and Torsion. These tests had different boundary conditions and forces applied, which were calculated considering an average case. The Factor of Safety obtained from these tests were taken as the ideal values. There would be loss in strength and stiffness after the chassis was built physically due to small misalignments, lack of perfect welding, certain dimensional errors and more.

### Trimming the Weldments and Creating Profiles

This was the most important part in terms of manufacturing. Proper trimming of all the joints were required in order to easily fit them after cutting the profiles. To prepare the chassis for this process, a colour code was followed to easily distinguish between tubes of three thicknesses - 2.5mm, 1.65mm and 1.2mm. After that, the process to convert the CAD Model to a physical model was as follows
1. Create a surface on each weldment with surface offset 0.
2. Flatten the surface separately by creating a very small slit.
3. Convert the flat surface to a drawing, and then print the PDF.
4. Paste the profile on tubes at proper lengths, and then cut the profiles.
5. Use fixtures designed earlier to align the tubes on a table.
6. Weld the joints and paint the chassis quickly to avoid rusting.

### Finalizing other components

After the key work of chassis design was completed, we proceded to the other departments' work. Mounts were designed and manufactured for all components - from suspension and brake pedals to battery and motor. 

### Documentation

To validate our 
