# About
this project was a way of us to try to make a new custom extension, but because of the complexity of the project , it will be deferred

# Extension

i think there is more than two ways to make custom extension i will describe them now

u can use python alongside C or C++ to make extension i think this is becuase to define new beaviour or to work with new types of data u need kind lower level language as C, C++ or even C#

i remember i have seen before someone did a custom extension using C#, but we dont use it , even if we use it we dont know how, so beucase of this we have to use different approaches and i mean to use the built-in extensions of OS to make our custom extension, i know it wont be professional but it will work

i can think of two ways to do it in this case,
but first i have to tell u about the requirements
the extension should have metadata + content of the file

we can do it by making the whole file a binary file so user cant modify the metadata and content directly and then create a viewer application which it views the content only and with this we have managed to store the metadata within the file

or we can make it a text file so user can content and then create and create hidden metadata file in somewhere in the os like in `local` directory, 

# what is the purpose of this of the file

the file will follow the indent-mechanism and for each block we will create a txt file has the content of this block by this way we can provide the user with organised study materials

# what is the purpose of the metadata

the metadata will be like this

`{"author": "John Doe", "creation_date": "2022-04-05", "keywords": ["example", "metadata"]}`

# how to use the .sa extension

we will make a cli or .exe file and add it to register and provide it into background shell and  we will provide a command to do all the jobs

so for now i think we will go for easy way and ignoring the metadata but if we have to use will we use the second way
