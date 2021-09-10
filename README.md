create new conda env with

conda create --name <env> --file requirements.txt

-loop over all dir in known face and :

    -loop over all img in every one dir and:

        -resize the img to 400*400 

        -encode the face in the img and register it to known_face var 
        and name of dir to names var

-open camera and serch for faces in every frame 

-compare fouded face with all encoded known face

- show the result in screen
