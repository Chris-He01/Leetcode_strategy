# Leetcode_strategy
- js reverse string: https://www.freecodecamp.org/news/how-to-reverse-a-string-in-javascript-in-3-different-ways-75e4763c68cb/
- remember to use hashmap for traverse/storage/checking 

# JavaScript code 
- array sort: stones.sort((a,b) => a-b);

#C++ 
- auto: 
  > for(auto &s : stones)
  > auto stone1 = sorted_stones.top(); sorted_stones.pop();
- return sorted_stones.size() ? sorted_stones.top() : 0;

# Java code 
- Hash Map:
  > Map<Character, Integer> pCount = new HashMap() or new HashMap<>();            
  > string to char: for (char ch : p.toCharArray());      
  > bool pCount.containsKey(ch);   
  > sCount.put(ch, 1);      
  > sCount.get(ch);      
  > sCount.remove(ch);     
- static methods means we can call the methods directly without initialize instances of the class; 
  > static methods can only access to static variables not instance variables. 
- vector: 
  > Vector<Integer> v = new Vector();      
  > v.addElement(1);
  > v.addElement(1);
- Stack<Character> ans = new Stack(); (notice the character)         
  > .push();      
  > .pop();
- Character.isDigit(stack.peek())   
- PriorityQueue
  > PriorityQueue<Integer> pq = new PriorityQueue(new Comparator<Integer>(){
            public int compare(Integer v1, Integer v2){
                return v2-v1;
            }
        });
        ```
   > 

# Leetcode_careful
- function return type matching
- string/char type matching
- function call
- different functions with different variable name
