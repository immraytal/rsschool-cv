# Andrei Kisel
### Software Engineer

---

### Contact information:

**Location:** Grodno, Belarus<br>
**E-mail:** mega.andrej2013@gmail.com<br>
[LinkedIn](https://www.linkedin.com/in/immraytal/) <br>
[Telegram](https://t.me/immraytal)

---

### About Me


---

###Code sample

**Task:** String ends with?

**Solution:**
```
public class Kata {
  public static boolean solution(String str, String ending) {
    return str.length() >= ending.length() ? 
        str.substring(str.length() - ending.length()).equals(ending) : false;
  }
}
```