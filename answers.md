Hacking Panda the Bear's Resume

1. Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead.

profile = document.querySelector('.profile-image')
profile.src = "images/clouds-man.jpg"
