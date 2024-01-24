# UnityTask
First Task
public class Crickets : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        print("Crickets");
    }
}
Second Task
public class Crickets : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        Destroy(gameObject)
    }

    // Update is called once per frame
    void Update()
    {
       
    }
}
Bonus Task

public class Crickets : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position =new Vector3(-0.5f, 1, 0)
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position =new Vector3(0.5f, 1, 0)
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position =new Vector3(0.5f, 2, 0)
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position =new Vector3(-0.5f, 2, 0)
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position =new Vector3(0, 3, 0)
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position =new Vector3(0,0,0);
    }

    // Update is called once per frame
    void Update()
    {
       
    }
}

