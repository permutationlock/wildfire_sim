Wildfire Simulation
-------------------
Currently the simulation has the following features:
    - Trees drawn in single draw call with one VBO of gl triangles.
    - Can vary how long trees burn, how likely nearby trees are to
      catch fire, how many trees there are, how much height affects
      fire movement.
    - Trees start burning, burn from a low state up to a hot state,
      then down unil they die out.  Trees around have a higher
      chance of catching on fire when the tree is burning hotter.
    - Trees have a height between 0.0 and 1.0, fire has a higher
      chance of moving uphill.
    - I have several research papers I read on forest fire
      simulations, but a lot of their equations were fairly abstract,
      but I do plan to implement some of that information and get
      more realistic fire.
      
What I plan to do:
    - Add wind.
    - Maybe add trees growing back and have a sort of life cycle sim.
    - Maybe improve tree appearance.
