using UnityEngine;

public class PlayerProfile : MonoBehaviour
{
    int health = 100;
    string playerName = "Asad";
    string playerWeapon = "ShotGun";
    int playerBullets = 99;

    bool isAlive = true;

    char rank = 'S';
    char batch = 'I';

    float speed = 7.5f;
    float mana = 80f;

    void Start()
    {
        Debug.Log(
            "PLAYER PROFILE\n" +
            "Health: " + health + "\n" +
            "Player Name: " + playerName + "\n" +
            "Player Weapon: " + playerWeapon + "\n" +
            "Player Bullets: " + playerBullets + "\n" +
            "Is Alive: " + isAlive + "\n" +
            "Rank: " + rank + "\n" +
            "Batch: " + batch + "\n" +
            "Speed: " + speed + "\n" +
            "Mana: " + mana
        );
    }
}