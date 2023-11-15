FORMAT: 1A
HOST: https://polls.apiblueprint.org/

# Contoh API e-commerce by Sandi S

Sandi Sukoco Putro (362258302037)

Polls is a simple API allowing consumers to view polls and vote in them.


# Group Product


## Search Collection [/api/v1/search]


### Search for Product Data [POST]

- Request (application/json)

        {
        "key": "authentic"
        }


- Response 200 (appliction/json)

        {
        "data" : [
                    {
                        "name": "Argentina Authentic Jersey 2018",
                        "brand": "Adidas",
                        "price": "$130",
                        "picture": "https://www.goalinn.com/f/13669/136697631/adidas-argentina-away-jersey-ss.jpg"
                    },
                    {
                        "name": "Brazil Authentic Jersey 2018",
                        "brand": "Nike",
                        "price": "$165",
                        "picture": "https://images.sportsdirect.com/images/products/37123413_l.jpg"
                    }
        ]
        }






##Questions Collection [/questions]