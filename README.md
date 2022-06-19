# pymunk-pinball-paulista

![output](https://user-images.githubusercontent.com/3694604/174443509-0e8fa474-2ced-461c-93a8-ac64ccb1699a.gif)

This was built at Sesc Avenida Paulista, 2D simulations workshop with @introscopia, Adriana Lessa, @claromes, Zuleide, @gilfuser.

TO DO:
- Rename/translate some variable names, like:
  * pontos -> score
  * LPb -> left_paddle_body
- I'd like to return the body from the building functions and add some keyword arguments:
   ```
    # now
    build_box(468, 620, 32, 30, static=False)
    plunger = shapes[-1].body
    shapes[-1].friction = 0
    shapes[-1].elasticity = 0 
   
    # better
    plunger = build_box(468, 620, 32, 30, static=False, friction=0, elasticity=0)
   
   ```
- Gil wants to add sound...

