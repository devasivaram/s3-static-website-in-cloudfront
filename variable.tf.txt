variable "region" {
}

variable "access_key" {
}

variable "secret_key" {
    
}

variable "project" {
    
}

variable "bucketname" {

}

 
 variable "default_root" {

 }

 variable "price" {

}

 variable "acmarn" {

}

## You need to use the mime type, otherwise you will get an error while loading the website.

variable "mime_types" {
  default = {
    htm   = "text/html"
    html  = "text/html"
    css   = "text/css"
    ttf   = "font/ttf"
    json  = "application/json"
    png	  = "image/png"
    jpg  = "image/jpeg"    
    woff2 = "font/woff2" 
    woff  = "font/woff"
    eot	  = "application/vnd.ms-fontobject" 
    js	  = "text/javascript"
    otf   = "font/otf"
    svg   = "image/svg+xml"
    txt   = "text/plain"
 }
}