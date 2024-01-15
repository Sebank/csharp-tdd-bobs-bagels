``
1.
As a member of the public,
So I can order a bagel before work,
I'd like to add a specific type of bagel to my basket.``

| Classes         | Methods                                     | Scenario                    | Outputs |
|-----------------|---------------------------------------------|-----------------------------|---------|
| `Core`		  | `add(string bagel)`							| Adds bagel to basket		  | void    |

``
2.
As a member of the public,
So I can change my order,
I'd like to remove a bagel from my basket.
``

| Classes         | Methods                                     | Scenario                    | Outputs |
|-----------------|---------------------------------------------|-----------------------------|---------|
| `Core`		  | `remove(string bagel)`						| Removes bagel from basket	  | void    |


``
3.
As a member of the public,
So that I can not overfill my small bagel basket
I'd like to know when my basket is full when I try adding an item beyond my basket capacity.
``

| Classes         | Methods                                     | Scenario                    | Outputs |
|-----------------|---------------------------------------------|-----------------------------|---------|
| `Core`		  | `add(string bagel)`							| Adds bagel to basket, and checks if baset is full| bool    |

``
4.
As a Bob's Bagels manager,
So that I can expand my business,
I�d like to change the capacity of baskets.
``
| Classes         | Methods                                     | Scenario                    | Outputs |
|-----------------|---------------------------------------------|-----------------------------|---------|
| `Core`		  | `changeCapacity(int capacity)`				| Changes capacity of basket  | void    |


``
5.
As a member of the public
So that I can maintain my sanity
I'd like to know if I try to remove an item that doesn't exist in my basket.
``
| Classes         | Methods                                     | Scenario                    | Outputs |
|-----------------|---------------------------------------------|-----------------------------|---------|
| `Core`		  | `remove(string bagel)`						| Removes bagel from basket, if it exists| bool    |