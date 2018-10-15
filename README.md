# Generics

**Example to create a generic Node in DLL(double linked list).**


-->class Node<T extends Comparable<T>>   /* This creates a Node of Type  "T" --> T must be of type
  Comparable i.e it has to be a class or interface which implements Comparable interface.*/
  
-->class Node<T extends Comparable<T>> implements Comparable<Node<T>> /*This will makes you to override the compareTo method for giving our own implementation for checking the equality of the Node<?>.
 
  @
  class Node<T extends Comparable<T>>
  {
     public T data;
     public Node<T> left;
     public Node<T> right;
  
     @Override
     public int compareTo(Node<T> o)
     {
     
     }
  
  
  
   }


