- In a Python file, enter the following code:

    ```python
    from sense_hat import SenseHat
    sense = SenseHat()
    sense.clear()

    o = sense.get_orientation()
    pitch = o["pitch"]
    roll = o["roll"]
    yaw = o["yaw"]
    print("pitch {0} roll {1} yaw {2}".format(pitch, roll, yaw))
    ```

    <iframe src="https://trinket.io/embed/python/c2009c972b" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

- When you run the program, you should see something like this:

    ```bash
    pitch 356.35723002363454 roll 303.4986602798494 yaw 339.19880231669873
    ```
