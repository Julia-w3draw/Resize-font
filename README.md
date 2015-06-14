# Resize-font

How to make your typography responsive.

The following example shows a simple solution that solves RWD on font problem by dynamically changing one element's font size accordingly every time the window adjusts its size. It is based on a statistical empirical determination of a linear equation: 

    font_size=minimal_constant + multiplier_constant*significant_reference 
    
 where minimal_constant is the minimum size a font can take, multiplier_constant is the empirically determined constant that ensures the readability and the reference is usually the width of a certain container, in this case "body".
