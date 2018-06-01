using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class NumberWizard : MonoBehaviour
{

    int maxNum = 1000;
    int minNum = 1;
    int guess = 500;

    // Use this for initialization
    void Start()
    {
        Debug.Log("Welcome to number wizard");
        Debug.Log("You need to pick a number");
        Debug.Log("The highest number you can pick is: " + maxNum);
        Debug.Log("The lowest number you can pick is: " + minNum);
        Debug.Log("Tell me if your number is higher or lower than 500");
        Debug.Log("Push Up = Higher, Push Down = Lower, Push Enter = Correct");
    }

    // Update is called once per frame
    void Update()
    {
        if (Input.GetKeyDown(KeyCode.UpArrow))
        {
            Debug.Log("Up Arrow key was pressed. ");
            minNum = guess;
            Debug.Log(guess);
        }
        else if (Input.GetKeyDown(KeyCode.DownArrow))
        {
            Debug.Log("Down Arrow key was pressed.");
            maxNum = guess;
            Debug.Log(guess);
        }
        else if (Input.GetKeyDown(KeyCode.Return))
        {
            Debug.Log("You hit enter");
        }

    }

}
