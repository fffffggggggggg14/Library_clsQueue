✅ 📄 وصف README احترافي لـ clsQueue
clsQueue

A high-level generic Queue implementation in C++ built on top of a custom Doubly Linked List.
The clsQueue<T> class provides a clean, flexible, and efficient FIFO data structure with extended capabilities beyond the standard library queue.

🚀 Features
✔ Generic Template Support

Works with any data type (int, string, structs...).

✔ FIFO Behavior

Implements queue operations efficiently using a doubly linked list.

✔ Core Queue Operations

push() — Add element to the back

pop() — Remove element from the front

front() — Access first element

back() — Access last element

size() — O(1) size retrieval

empty() — Check if queue is empty

✔ Extended Functionality

Unlike standard std::queue, this implementation supports:

Access by index: get(index)

Update elements: update(index, value)

Insert at front/back

Insert after index

Reverse the entire queue

Detailed printing

Clear queue contents

📦 Example Usage
#include "clsQueue.h"

int main() {
    clsQueue<int> q;

    q.push(10);
    q.push(20);
    q.push(30);

    cout << q.front(); // 10
    cout << q.back();  // 30

    q.pop();
    q.print(); // 20 30

    return 0;
}

🛠 Implementation Notes

Internally uses clsDoublyLinkedList for dynamic storage.

All operations are safe and exception-free.

Easily extendable for custom data structures.

📄 License

Free to use for learning, academic projects, and development.
