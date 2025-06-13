# finch-robot

### Development Checklist

| Completed | Task         | Description |
|:---------:| :-----------:|:------------|
|    ✅     | Familiarize  | Learn how to: <ul><li>Connect to the robot</li><li>Interpret what built-in sensors detect</li><li>Program basics in SNAP!</li><li>Setup local developing environment to code in Java</li></ul>|
|    ✅     | 3D Design    | Designed a 3d model that allows the storage of coin like objects|
|    ✅     | Develop Code | Develop a code to allow the finch robot to move in all directions using keybinds|

---

<details>
  
<summary><strong>Inspiration for the Project</strong></summary>

The creation of a finch robot that implements the controls of an average video game; which allows for WASD keyboard inputs along with a toggle sprint system which quickens the speed of the robot's movement.

</details>

---

### Design Cycle
<img src="design_cycle.png" alt="design cycle" width="300" height="300">

###### Include commentary on your experience with the design cycle during this project

---

### Code to Highlight
```java
        JFrame frame = new JFrame("gui");
        frame.setSize(500, 500);
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        
        frame.setLayout(new FlowLayout());
        //static JFrame text = new JFrame("textfield");;
        
        JButton forwardBot = new JButton("Forward");
        forwardBot.addActionListener(e -> {
            System.out.println("forward");
            f.setMove("F",100,100);
        });
        
        JButton backwardsBot = new JButton("Backward");
        
        backwardsBot.addActionListener(e -> {
            System.out.println("backward");
            f.setMove("B",100,100);
        });
```

---

### What was your motivation?
We thought it was a good idea to 3D print a container to carry coin like objects, this can be used to store coins and can be modifed to hold bigger objects, possibly a cup holder. 

### What did you learn?
While coding the robot, we as a group established the fact that we wanted to utilize WASD keybinds in order to enable the finch's movement. We collectly agreed to have this be our primary goal for the finch, because we wanted the ability to have free control of the robot while it was active, and it felt too much off a hassle to constantly change the code if we wanted the flinch to perform a different task. We also thought that it would've been a suitable implementation to add onto the flinch, considering the fact that our 3D printed modification would only had a decorative purpose.

We figured out how 
  
### What makes your project stand out?
We used two different programming libraries: jswing and keyevents.
