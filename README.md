# Shaders & Triangles: Interactive 3D Color-Shifting Cube

This project showcases an interactive, color-shifting 3D cube using pure CSS. It demonstrates advanced CSS techniques including 3D transforms, custom properties, and animations.

## Features

- Seamless color transition using CSS custom properties
- 3D rotation animation
- Interactive hover effects
- Responsive design using viewport units

## Design Implications

This project exemplifies how complex, interactive 3D visualizations can be created using only CSS. It pushes the boundaries of what's possible in web design without relying on JavaScript or WebGL.

Key design aspects:

1. **Color Theory**: The use of HSL color space allows for smooth, natural color transitions.
2. **3D in 2D**: Demonstrates techniques for creating the illusion of 3D objects on a 2D screen.
3. **Interaction Design**: The hover effect provides immediate visual feedback, enhancing user engagement.

## Customization

The design is highly customizable. Here are some elements you can easily modify:

- Change the `--clr` variable in the `.cont` class to alter the base color.
- Adjust the `width` and `aspect-ratio` of the `.box` class to change the cube's size and shape.
- Modify the `animation-duration` in the `.cont` and `.box` classes to change the speed of color transition and rotation.

## Experimentation Ideas

1. Try changing the gradient patterns to create different textures on the cube faces.
2. Experiment with different `transform` values to create unique 3D shapes.
3. Add more interactive elements, such as click events or scroll-based animations.
4. Incorporate this design into a larger UI component, like a loading indicator or navigation menu.

I encourage you to fork this project and push the boundaries of CSS-based 3D design!