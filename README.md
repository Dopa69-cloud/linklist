Step 1: Start

Begin the program execution.

🔹 Step 2: Define the Node Class

1.create a class named Node with:

>An integer variable data to store the value of the node.

>A pointer next of type Node* to store the address of the next node.

A constructor that:

>Takes an integer as input.

>Initializes data with the input value.

>Initializes next with NULL.

>A member function display() to:

Print the value of data.

Print the memory address stored in next.

🔹 Step 3: Create a Node in main()

In the main() function:

Create a pointer l1 of type Node*.

Use new to dynamically allocate a new Node with value 8.

l1 now points to this new node.

🔹 Step 4: Call the display() Function

Use the pointer l1 to call the display() function.

The function prints:

The value stored in data (which is 8).

The address in next (which is NULL, or shown as 0 or (nil) depending on the system).

🔹 Step 5: End Program

Return from the main() function.

Program ends successfully.
