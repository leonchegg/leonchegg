using UnityEngine;

public class ClickBtn : MonoBehaviour
{
    public AudioSource click;
    public AudioClip clickBtn;

    void ClickButton()
    {
        click.PlayOneShot(clickBtn);
    }
}
