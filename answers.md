Hacking Panda the Bear's Resume

1. Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead.

profile = document.querySelector('.profile-image')
profile.src = "images/clouds-man.jpg"

1b. Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.

sky = document.querySelector('#left-image.portfolio-image img')
sky.src = "images/pikachu-drawing.jpg"
