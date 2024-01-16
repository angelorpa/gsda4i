# gsda4i: Graphical Screen Design Aid for IBM i

a WYSIWYG graphical interface for designing IBM i (AS400) display files.

# TODO 
## Graphical Interface
- Implement a WYSIWYG graphical interface for designing AS400 display files. This could involve creating a canvas where users can drag and drop elements like fields, constants, subfiles, etc.
- Allow users to set properties for each element, such as field names, lengths, positions, and attributes.

## JSON Representation
- Create a data structure that represents the design elements in a JSON format. Each element on the screen (field, constant, subfile, etc.) should correspond to a JSON object.
- Update the JSON structure dynamically as the user modifies the design.

## Conversion Logic
- Develop the logic to convert the JSON representation into postional DDS for Display files and viceversa.
- Map the graphical properties to the appropriate DDS keyworkds.

## Validation and Error Handling
- Implement validation checks to ensure that the design adheres to DDS display file standards.
- Provide informative error messages and suggestions for corrections.
