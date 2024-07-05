# iOS-Job-Interview-Guide-book
You will find the comprehensive list to prepare for iOS developer interview 
## 1. General programming:
-OOPS: Object Oriented Programming 
- Classes
  - Encapsulation
  - Access Control 
  - Abstraction
  - Namespace
  - Expressive Syntax
  - Extensibility
  - Inheritance 
  
## 2. UIKit:
1. iOS App life cycle
2. UIKit -> Notifications - Local and Remote notifications
3. UIKit -> UITableView & UICollectionView 

## 3. SwiftUI:

## 4. Swift:
### 1. Value type vs Reference type 

### 2. Protocol Oriented Programming 
- Heart of the Swift programming laungaue design
 With the struct and enum (Value type) can implement access control, abstraction, namespce.

Points with the classes
1. Implicit sharing (Automatic Sharing) - Defencive copying, inefficiency, race condition, locks, more inefficiency, deadlock, complexity, bugs
2. Class inheritance is intrusive - single inheritance - weight gain, no retropective modeling, super class may have stored properties, you must accept them in sub class, initialization burden, don't break superclass invariants.
3. Class bad fit for problems where type relationships matter. Classes don't allow us to define crucial type relationship. 

But when to use classes
- When you want implicit sharing
   - Copying or comparing instances doesn't make sense (e.g., Windows)
   - Lifetime of instances are tied to external effects (e.g., Temporary files - created and destroyed)
   - Insatnces are just sinks - write-only conduits to external state (e.g., CGContext)
   - If a framework expects you to subclass, or to pass an object, do! (Cocoa, CocoaTouch)
   - 
Swift collections are value types. Values - don't share 

#### Better abstraction mechanism
1. Supports value types (and classes)
2. Supports static type relationships (and dynamic dispatch)
3. Non-monolithic
4. Supports retroactive modeling
5. Doesn't impose instance data on models
6. Doesn't impose initialization burdens on models
7. Makes clear waht to implement

   Protocols have all the above advantages.

   Swift is Protocol Oriented Programming (POP)
   Start with Protocol - don't start with class
   Self -> Its placeholder, where the type confirms to that protocol.

   Deciplined decoupling is beautiful thing.

   Protocols and Generics for Testablility.
   Protocl Extension: Implemenation is shared among the adopter
   Constrained Extension - You can define with the "Where"
   Retroactive adoption
   
## Difference between static dispatch and dynamic dispatch
   
   


