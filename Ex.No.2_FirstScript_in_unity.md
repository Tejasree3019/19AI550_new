# Ex.No: 2  Welcome Script in Unity
### DATE:  31.10.26                                                                         
### REGISTER NUMBER : 212224240168 
### AIM: 
 To learn the basic scripting in Unity and print welcome message in Console window. 
### Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.
### Program 
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class FirstScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        print("Welcome to Unity");
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
```
### Output:

<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/a1576f0a-9981-49b8-a22b-270890625c56" />
<img width="1917" height="851" alt="image" src="https://github.com/user-attachments/assets/5d2fa5c7-b0b1-4abb-baa6-566804783a6a" />


### Result:
Thus the welcome script was printed on Console Window  sucessfully.

