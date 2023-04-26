# Structure
Structure in c is a user-defined data type that enables us to store the collection of different data types. Each element of a structure is called a member.
Structures ca; simulate the use of classes and templates as it can store various information
The ,struct keyword is used to define the structure.

We can declare a variable for the structure so that we can access the member of the structure easily. 
 The member access operator is coded as a period between the structure variable name and the structure member that we wish to access.

Accessing members of the structure , it can be done in two ways:

By . (member or dot operator)

By -> (structure pointer operator)




SYNTAX:

struct structure_name   
{  
    data_type member1;  
    data_type member2;  
    .  
    .  
    data_type memeberN;  
};  
<variable declaration>;            \\ before main
};

struct <name_of_structure><name_of_variable>;           \\ can be declared inside main
