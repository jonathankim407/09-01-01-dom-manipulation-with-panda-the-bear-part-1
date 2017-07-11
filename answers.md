Hacking Panda the Bear's Resume

1. Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead.

profile = document.querySelector('.profile-image')
profile.src = "images/clouds-man.jpg"

1b. Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.

sky = document.querySelector('#left-image.portfolio-image img')
sky.src = "images/pikachu-drawing.jpg"

2. Select the heading that says "Panda the Bear" and change it to your own name.

heading = document.querySelector('h1.highlight')
heading.innerText = 'Jonathan Kim'

3. Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector)

employment = document.querySelector('#employment h3.info-title')
employment.innerText = 'Funemployment'

4. Change the colour of the body.

body = document.querySelector('body')
body.style.backgroundColor = 'red'

5. Change the colour used by the highlight class.

highlight = document.querySelectorAll('.highlight')
highlight.forEach(function(item) {item.style.color = 'blue'})

6. Change the font family of the h1 to 'monospace'.

heading = document.querySelectorAll('h1')
heading.forEach(function(item) {item.style.fontFamily = 'monospace'})

7. Find a way to select the round icons in the sidebar and then change their colour.

icon = document.querySelectorAll('a.action-icon-bg')
icon.forEach(function(item) {item.style.backgroundColor = 'red'})
