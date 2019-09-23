# README

Initial rails commands:

$ rails new buildcar
$ cd buildcar
$ rails generate scaffold Part name:string
$ rails generate scaffold Make name:string country:string
$ rails generate scaffold Car model:string make:references vin:string
$ rails generate model CarsParts part:references car:references
$ rails db:migrate

Things learned:

I learned how to create a fairly basic forms web application that uses several SQL tables, as well as how to connect them properly and be able to input, save and edit information. What I struggled with the most was the forms pages, which I figured out had largely to do with the naming of the model used to connect the Part and Car tables/objects. The other pieces were easier to figure out.
