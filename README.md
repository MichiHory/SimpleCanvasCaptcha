# SimpleCanvasCaptcha
Simple Captcha generated in canvas element

## How to use
Just copy > pasete content of captcha.html to file, where you need it

If you do not want to create your own styles, you can use styles in captcha.css

Again, just copy > paste work

### Important

In javascript, there is validate method which was used to verify via php script,

You can remove the $post part and use just verifying via javascript like:
`sessionStorage.setItem("verified", "true");
return true;`

Or, you can use own php script to complete verification
