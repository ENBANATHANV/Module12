# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
      stack = []
      
      for i in range(3):
          value = input(f"Enter value {i + 1}: ")
          stack.append(value) 
      
      top_element = stack[-1]
      print("Top element of the stack is:", top_element)


## Output
![image](https://github.com/user-attachments/assets/9015bc63-f158-4ca7-84ec-0122052dc4c9)


## Result
Thus, the program has been execueted successfully.
