# Discord Bot Website Template! - Degisned and made by FURY!

 Cool and beautiful looking website made with ❤️! [Live Demo](https://kacktide.github.io/Discord-Bot-Website-Template/).
 
Built with HTML, CSS & Javascript!


# Includes:
> Mordern Design

> 85% Responsive/Mobile friendly. 

> Fully customizable

> Free

> Features section

> Animated approximate counter (Servers, User, Channels)

> Custom Overflow (Scrollbar)

> SEO optimisation
# Screenshots:

![First Section](https://cdn.discordapp.com/attachments/802859558925893672/862250268846456832/wweb1.PNG)

![Second Section](https://cdn.discordapp.com/attachments/802859558925893672/862250340367859722/feature.PNG)

![Third Section](https://cdn.discordapp.com/attachments/802859558925893672/862250727001554944/channels.PNG)

![Footer Section](https://cdn.discordapp.com/attachments/802859558925893672/862250790433325056/asdasdasdasdasdadasdadsa.PNG)

# Tutorial
 **SEO**
 
 ![Embeded Links](https://cdn.discordapp.com/attachments/802859558925893672/862266283620958228/unknown.png)
 > How to edit(Steps)
  1. Go to `index.html`.
  2. Go to head and you can find a html comment for SEO/ Embeded Links
  3. Replace the sample text to fit your needs!


If you need any help you can contact via discord @ FURY#6969.

Please give a ⭐ if you like this project.

15 Stars = Commands Page with search!

Feel free to open an pull request if you encounter an error!
var copy = function(target) {
    var textArea = document.createElement('textarea')
    textArea.setAttribute('style','width:1px;border:0;opacity:0;')
    document.body.appendChild(textArea)
    textArea.value = target.innerHTML
    textArea.select()
    document.execCommand('copy')
    document.body.removeChild(textArea)
}

var pres = document.querySelectorAll(".comment-body > pre")
pres.forEach(function(pre){
  var button = document.createElement("button")
  button.className = "btn btn-sm"
  button.innerHTML = "copy"
  pre.parentNode.insertBefore(button, pre)
  button.addEventListener('click', function(e){
    e.preventDefault()
    copy(pre.childNodes[0])
  })
})

# Thanks for using this template and reading this! 
