# Intuition
<!-- Describe your first thoughts on how to solve this problem. -->
- The goal of this code is to defang an IP address by replacing each dot '.' with "[.]".
---


# Approach
<!-- Describe your approach to solving the problem. -->

## *Certainly! Here's the approach explained in bullet points:*

1. Input:
    - The function defangIPaddr takes a string address representing an IP address.
2. Initialization:
    - Initialize an empty string s to store the defanged IP address.
3. Iterate through the characters:
    - Use a for loop to iterate through each character in the input string address.
4. Defanging:
    - If the current character is a dot ('.'), append "[.]" to the string s.
    - If the current character is not a dot, simply append the character to the string s.
5. Return:
    - After processing all characters, return the final defanged IP address stored in the string s.

---


# Complexity
**- Time complexity:**
<!-- Add your time complexity here, e.g. $$O(n)$$ -->
- **Time Complexity: O(n)**, *where n is the length of the input string address.*

**- Space complexity:**
<!-- Add your space complexity here, e.g. $$O(n)$$ -->
- **Space Complexity: O(n)**, *where n is the length of the input string address.*
