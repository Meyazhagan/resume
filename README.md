# Overview of problem

    King Shan is the emperor of Lengaburu and has been ruling the 
    planet for the last 350 years ( they have long lives in Lengaburu, you 
    see! ). Lets write some code to get to know the family.

    https://www.geektrust.in/coding-problem/backend/family

# Steps to build the code

    > run command - mvn clean install

# Steps to run the code

    > run command - java -jar target/geektrust.jar path-to-input-file

# Steps to run the program with your own family tree

    create family tree file format like
    ADD_PLANET "Planet_name" "king_name" "Queen_name"
    ADD_CHILD "mother_name" "child_name" "gender"
    ADD_SPOUSE "partner_name" spouse_name" "gender"

    > run command - java -jar target/geektrust.jar path-to-input-file path-to-your-own-family-tree-file

# Steps to test the code

    > run command - mvn verify