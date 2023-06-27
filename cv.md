## <p style="text-align: center;">[rsschool-cv]() </p>

# **Stanislau Zaitsau**
## Trainee\Junior Fullstack developer
---

## **Contact information**

**Phone:** +375(44)591-87-69

**Email:** krollikroddzer@mail.ru

**Telegram:** @KrollikRoddzer

**[LinkedIn](https://www.linkedin.com/in/krollikroddzer/)**

---

## **Personal profile**

Since the 10th grade in high school, I became interested in programming. My journey began with the Olympiads on sports programming and in this regard, I entered the Belarusian State University in the Faculty of Applied Mathematics and Computer Science. 

Now I am fond of programming in c# language and .NET platform. At the moment I'm writing File Cabinet App - it's a console application, similar to the database, only there is a fixed amount of data to enter. It also uses different programming patterns. 

As for my extracurricular activities I am fond of cycling, playing guitar and photography.

## **Skills and Proficiency**

* C#, .NET, ADO.NET, NUnit
* SQL, T-SQL, MS SQL Server
* C++, Qt
* Java, Java EE, Swing
* HTML5, CSS3
* Algorithms and Data Structures
* Design patterns
* Git, GitHub, GitLab

## **Code example**

This code in C# represents solution to task 'Two sum' from LeetCode. This [link](https://leetcode.com/problems/two-sum/) delivers you to the task.
```
public class Solution {
    public int[] TwoSum(int[] nums, int target) {
        for (int i = 0; i < nums.Length; ++i)
        {
            for (int j = i + 1; j < nums.Length; ++j)
            {
                if (nums[i] + nums[j] == target)
                {
                    return new int[] { i, j };
                }
            }
        }

        return new int[] {};
    }
}
```