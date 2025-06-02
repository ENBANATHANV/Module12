**# 🔁 Queue using Linked List: Display Front and Rear Elements of a Queue

## 🎯 Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---

## 🧠 Algorithm

1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.

---
## Program
      queue = []
      queue.append('a')
      queue.append('b')
      queue.append('c')
      queue.append('d')
      print('Initial Queue: ' ,queue)
      front=queue[0]
      rear=queue[-1]
      print("\nElement at the front of the queue is.... ", front)
      print("\nElement at the rear of the queue is ....", rear)


## Output
![image](https://github.com/user-attachments/assets/e2eb10bd-b8b3-4250-8bb1-c5b7b05a1d6d)


## Result
Thus, the program has been execueted successfully.**# # 📚 Stack using Linked List: Check and Display Whether the Stack is Full or Not

This Python program demonstrates how to check if a stack (using `LifoQueue` from the `queue` module) is full or not. It uses the `full()` method to determine the stack's status and then displays the appropriate message.

## 🎯 Aim

To write a Python program that:
- Creates a stack with a fixed size.
- Adds elements to the stack.
- Checks if the stack is full.
- Displays a message indicating whether the stack is full or not.

## 🧠 Algorithm

1. **Import the LifoQueue class**:
   - Import `LifoQueue` from the `queue` module to create the stack.

2. **Create a Stack**:
   - Instantiate a `LifoQueue` with a maximum size (e.g., 4).

3. **Add Elements to the Stack**:
   - Add elements (e.g., 'a', 'b', and 'c') to the stack using the `put()` method.

4. **Check if the Stack is Full**:
   - Use the `full()` method of `LifoQueue` to check if the stack has reached its maximum capacity.

5. **Display the Status**:
   - Print "Stack is full" if the stack is full.
   - Otherwise, print "Stack is not full".

## 📝 Program
      from queue import LifoQueue
      stack = LifoQueue(maxsize=4)
      stack.put('a')
      stack.put('b')
      stack.put('c')
      ifstack.full():
      print("Stack isfull")
      else:
      print("Stack is not full")

## Sample Input & Output
![image](https://github.com/user-attachments/assets/effe7fca-dcc7-4cf3-a919-6f10d10fed6f)


## Result
Thus, the program has been execueted successfully.
