using System.Collections;
using System.Collections.Generic;
using UnityEngine.UI;
using UnityEngine;

public class ToggleGroup : MonoBehaviour
{
    public Toggle t1;
    public Toggle t2;
    public Text tt;
    
    public void group()
    {
        if(t1.gameObject.activeInHierarchy == false)
        {
            t1.gameObject.SetActive(true);
        }
        else
        {
            t1.gameObject.SetActive(false);
        }
        if (t2.gameObject.activeInHierarchy == false)
        {
            t2.gameObject.SetActive(true);
        }
        else
        {
            t2.gameObject.SetActive(false);
        }
        if (tt.gameObject.activeInHierarchy == false)
        {
            tt.gameObject.SetActive(true);
        }
        else
        {
            tt.gameObject.SetActive(false);
        }
    }
}
