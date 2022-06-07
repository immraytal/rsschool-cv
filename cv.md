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

I'm a java software engineer, and I graduated from the university a one year ago.
I have almost 2 years enterprise experience. <br>
Before job, I successfully finished 2 long-term courses: <br>
- Java Web-development at EPAM
- Java Full Course from Junior to Middle at SENLA

My current project is signing service which provides signing without printing something on the paper.

I'd like to learn basics of JS and relevant technologies to become as full-stack developer.

So, I'm just enjoying life and I need interesting and good job to make new friends and have a good time.
I love to learn interesting things, listen music, analyze films and spend time with my friends. 
Who knows, maybe in future I'll to try scriptwriting or game development. 

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