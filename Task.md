# UNORDERED LIST

To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.

INPUT:

"- Task 1"
"* Task 3"
"+ Task 2"

OUTPUT:

- Task 1
* Task 3
+ Task 2
  
 To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

# ORDERED LIST

INPUT:
'1. Sample 1'
'2. Sample 2'
'3. Sample 3'
    '* Sample 3a'
    '* Sample 3b'
    
OUTPUT:    
1. Sample 1
3. Sample 3
   * Sample 3a
   * Sample 3b
2. Sample 2
   
 
# TASK LIST

- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del> 1
supported
- [x] list syntax required (any
unordered or ordered list
supported)



