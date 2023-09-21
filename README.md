(1) Download caduma_final.zip
(2) Naviagte intto caduma_final/ folder
(3) To run Code with preset comands:
    [a] ./run1.sh
            - runs with waves.png image.
            - output into output.png
    [b] ./run2.sh
            - runs with checkers.png image
            - output into output.png
    [c] ./run3.sh 
            - runs with Lena.png image
            - output into output.png
(4) To run Code bare:
    [a] make clean
    [b] make
    [b] ./final <input_image> <output_image>


(5) Once program is running:
    [a] Click image with left mouse button to apply color map
            - Program will take some time to run because some color
              palettes are giant.
    [b] Press 'r' or 'R' to revert image to original
    [c] Press 'w' or 'W' to write image to specified file. If no file
        specified, program will ask you to input one
    [d] Press 'f' or 'F' to input a new image file to map to
    [e] Press 'q' or 'Q' to exit program.