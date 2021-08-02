
paste this in console boom get auth bearer
`"Bearer" + document.cookie.split(";")[9].replace("bearer_token=", "")`

make this bookmark and u press it and get auth bearer
`javascript:document.body.innerHTML = "Bearer" + document.cookie.split(";")[9].replace("bearer_token=", "")`
