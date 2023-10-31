## Ingenieria inversa


Se hace la busqueda en el sitio https://www2.hm.com/es_mx/search-results.html?q=zapatos

Donde la vista se ve de la siguiente manera 
![Home](/assets/main.png "Home")

En la busqueda del api que se consume para dar los resultados de busqueda es la siguiente

[Api de Búsqueda de H&M](https://w9ea975b8.api.esales.apptus.cloud/api/v2/panels/slp?esales.sessionKey=2ee8d3b6-da7d-4dec-9655-45dd01f0261f&esales.customerKey=2ee8d3b6-da7d-4dec-9655-45dd01f0261f&esales.market=MX&market_locale=es_mx&search_prefix=zapatos&search_phrase=zapatos)
En la busqueda del api que se consume para dar los resultados de busqueda es la siguiente
* https://w9ea975b8.api.esales.apptus.cloud/api/v2/panels/slp?esales.sessionKey=2ee8d3b6-da7d-4dec-9655-45dd01f0261f&esales.customerKey=2ee8d3b6-da7d-4dec-9655-45dd01f0261f&esales.market=MX&market_locale=es_mx&search_prefix=zapatos&search_phrase=zapatos


### Respuesta de la busqueda 
```json
{
    "autocomplete": [
        {
            "name": "autocomplete",
            "ticket": "Oy9zbHAvYXV0b2NvbXBsZXRlOyM7IzsjOyM7IzsjOyM7",
            "path": "/slp/autocomplete",
            "description": "Suggests complete search phrases for the search box.",
            "displayName": "Autocomplete",
            "attributes": {},
            "resultType": "completions",
            "completions": [
                {
                    "text": "zapatos",
                    "relevance": 2.570796275927224
                },
                {
                    "text": "zapatos sin talón",
                    "relevance": 0.09258070001318992
                },
                {
                    "text": "zapatos mule",
                    "relevance": 0.08144510000222525
                },
                {
                    "text": "zapatos derby",
                    "relevance": 0.0682410000087896
                },
                {
                    "text": "zapatos con aplicaciones",
                    "relevance": 0.033268400009123386
                }
            ]
        }
    ],
    "nonProductSuggestions": [
        {
            "name": "non-product-suggestions",
            "ticket": "Oy9zbHAvbm9uLXByb2R1Y3Qtc3VnZ2VzdGlvbnM7IzsjOyM7IzsjOyM7Izs",
            "path": "/slp/non-product-suggestions",
            "description": "Suggests products based on completions of search phrases for the search box.",
            "displayName": "Non Product Suggestions",
            "attributes": {},
            "resultType": "products",
            "products": []
        }
    ],
    "productSuggestions": [
        {
            "name": "product-suggestions",
            "ticket": "Oy9zbHAvcHJvZHVjdC1zdWdnZXN0aW9uczsjOyM7IzsjOyM7IzsjOw",
            "path": "/slp/product-suggestions",
            "description": "Suggests products based on completions of search phrases for the search box.",
            "displayName": "Product Suggestions",
            "attributes": {},
            "resultType": "products",
            "products": [
                {
                    "key": "1076691_group_006_es_mx",
                    "ticket": "Oy9zbHAvcHJvZHVjdC1zdWdnZXN0aW9uczsjO3Byb2R1Y3Rfa2V5OzEwNzY2OTFfZ3JvdXBfMDA2X2VzX214OzEwNzY2OTEwMDZfZXNfbXg7T0JKRUNUSVZFJDtOT05FOk5PTkU7NDA7",
                    "variants": [
                        {
                            "key": "1076691006_es_mx",
                            "ticket": "Oy9zbHAvcHJvZHVjdC1zdWdnZXN0aW9uczsjO3Byb2R1Y3Rfa2V5OzEwNzY2OTFfZ3JvdXBfMDA2X2VzX214OzEwNzY2OTEwMDZfZXNfbXg7T0JKRUNUSVZFJDtOT05FOk5PTkU7NDA7",
                            "attributes": {
                                "v_actual_price": [
                                    "1699.0"
                                ],
                                "v_allocation_flag": [
                                    "false"
                                ],
                                "v_article_code": [
                                    "1076691006"
                                ],
                                "v_article_name": [
                                    "Botas a la rodilla"
                                ],
                                "v_article_order": [
                                    "1"
                                ],
                                "v_article_type": [
                                    "Z001"
                                ],
                                "v_available_size_codes": [
                                    "005",
                                    "006",
                                    "007",
                                    "008",
                                    "009",
                                    "010",
                                    "011"
                                ],
                                "v_available_size_options": [
                                    "4",
                                    "5",
                                    "6",
                                    "7",
                                    "8",
                                    "9",
                                    "10",
                                    "11"
                                ],
                                "v_available_size_rate": [
                                    "88"
                                ],
                                "v_available_sizes": [
                                    "5",
                                    "6",
                                    "7",
                                    "8",
                                    "9",
                                    "10",
                                    "11"
                                ],
                                "v_blueprice": [
                                    "0.0"
                                ],
                                "v_categories_names": [],
                                "v_color": [
                                    "Black"
                                ],
                                "v_color_code": [
                                    "000000"
                                ],
                                "v_color_filter": [
                                    "Negro_000000"
                                ],
                                "v_color_loc": [
                                    "Negro"
                                ],
                                "v_colour_description": [
                                    "Negro"
                                ],
                                "v_colour_groups": [
                                    "Negro"
                                ],
                                "v_colour_shades": [
                                    "Carbón"
                                ],
                                "v_coming_soon": [
                                    "false"
                                ],
                                "v_composition_types": [
                                    "Forro",
                                    "Forro",
                                    "Pala",
                                    "Suela"
                                ],
                                "v_construction": [
                                    "Others"
                                ],
                                "v_currency_iso": [
                                    "MXN"
                                ],
                                "v_currency_symbol": [
                                    "$"
                                ],
                                "v_currentlyForSaleOnSite": [
                                    "true"
                                ],
                                "v_description": [
                                    "Botas a la rodilla con presilla posterior. Forro de satín y suelas gruesas con diseño en la parte inferior. Altura de las suelas 5 cm."
                                ],
                                "v_fashion_image": [
                                    "https://lp2.hm.com/hmgoepprod%3Fset%3Dsource%5B%2Fed%2F57%2Fed578ed96f60439a308ff47279ffa2aff44fbd4e.jpg%5D%2Corigin%5Bdam%5D%2Ccategory%5Bladies_shoes_boots%5D%2Ctype%5BDESCRIPTIVESTILLLIFE%5D%2Cres%5Bm%5D%2Chmver%5B2%5D%26call%3Durl%5Bfile%3A%2Fproduct%2Fmain%5D"
                                ],
                                "v_fashion_image_base_url": [
                                    "https://image.hm.com/assets/hm/ed/57/ed578ed96f60439a308ff47279ffa2aff44fbd4e.jpg"
                                ],
                                "v_formatted_blueprice": [
                                    ""
                                ],
                                "v_formatted_price": [
                                    "$1,699.00"
                                ],
                                "v_formatted_prior_price": [
                                    ""
                                ],
                                "v_formatted_yellowprice": [
                                    ""
                                ],
                                "v_functions": [],
                                "v_gallery_images": [
                                    "https://lp2.hm.com/hmgoepprod%3Fset%3Dsource%5B%2F80%2Fde%2F80de00dd37cb8633245dd6fb8f8406a97a1f4089.jpg%5D%2Corigin%5Bdam%5D%2Ccategory%5Bladies_shoes_boots%5D%2Ctype%5BDESCRIPTIVESTILLLIFE%5D%2Cres%5Bm%5D%2Chmver%5B2%5D%26call%3Durl%5Bfile%3A%2Fproduct%2Fmain%5D",
                                    "https://lp2.hm.com/hmgoepprod%3Fset%3Dsource%5B%2F8d%2F67%2F8d6743ee6a7f1f078fa47185a0409e13d41f4046.jpg%5D%2Corigin%5Bdam%5D%2Ccategory%5Bladies_shoes_boots%5D%2Ctype%5BDESCRIPTIVEDETAIL%5D%2Cres%5Bm%5D%2Chmver%5B2%5D%26call%3Durl%5Bfile%3A%2Fproduct%2Fmain%5D",
                                    "https://lp2.hm.com/hmgoepprod%3Fset%3Dsource%5B%2Fdc%2F25%2Fdc2579fa15399ba9c7a03eaa5d2ab1766ad8a4ed.jpg%5D%2Corigin%5Bdam%5D%2Ccategory%5Bladies_shoes_boots%5D%2Ctype%5BDESCRIPTIVEDETAIL%5D%2Cres%5Bm%5D%2Chmver%5B2%5D%26call%3Durl%5Bfile%3A%2Fproduct%2Fmain%5D"
                                ],
                                "v_gallery_images_base_url": [
                                    "https://image.hm.com/assets/hm/80/de/80de00dd37cb8633245dd6fb8f8406a97a1f4089.jpg",
                                    "https://image.hm.com/assets/hm/8d/67/8d6743ee6a7f1f078fa47185a0409e13d41f4046.jpg",
                                    "https://image.hm.com/assets/hm/dc/25/dc2579fa15399ba9c7a03eaa5d2ab1766ad8a4ed.jpg"
                                ],
                                "v_has_blueprice": [
                                    "false"
                                ],
                                "v_has_yellowprice": [
                                    "false"
                                ],
                                "v_hybris_color_code": [
                                    "09"
                                ],
                                "v_imagesID_list": [],
                                "v_is_old_sale": [
                                    "false"
                                ],
                                "v_is_on_sale": [
                                    "false"
                                ],
                                "v_is_online": [
                                    "true"
                                ],
                                "v_is_preshopping": [
                                    "false"
                                ],
                                "v_link_pdp": [
                                    "/es_mx/productpage.1076691006.html"
                                ],
                                "v_material_name": [
                                    "poliuretano",
                                    "Goma termoplástica",
                                    "poliuretano",
                                    "poliéster"
                                ],
                                "v_member_label": [
                                    ""
                                ],
                                "v_new_from": [
                                    "2023/08/07"
                                ],
                                "v_pattern": [
                                    "Color sólido"
                                ],
                                "v_percentageDiscount": [
                                    ""
                                ],
                                "v_price": [
                                    "1699.0"
                                ],
                                "v_prior_price": [
                                    "0.0"
                                ],
                                "v_rgbcolor": [
                                    "#272628"
                                ],
                                "v_selling_attributes": [],
                                "v_shop_now_link": [
                                    "/es_mx/productpage/_jcr_content/product.quickbuy.1076691006.html"
                                ],
                                "v_size_filters": [
                                    "9_5_6_footwear",
                                    "14_10_6_footwear",
                                    "15_11_6_footwear",
                                    "11_7_6_footwear",
                                    "10_6_6_footwear",
                                    "13_9_6_footwear",
                                    "12_8_6_footwear"
                                ],
                                "v_size_scale": [
                                    "270"
                                ],
                                "v_size_scale_group": [
                                    "SG006"
                                ],
                                "v_still_life_image": [
                                    "https://lp2.hm.com/hmgoepprod%3Fset%3Dsource%5B%2Fed%2F57%2Fed578ed96f60439a308ff47279ffa2aff44fbd4e.jpg%5D%2Corigin%5Bdam%5D%2Ccategory%5Bladies_shoes_boots%5D%2Ctype%5BDESCRIPTIVESTILLLIFE%5D%2Cres%5Bm%5D%2Chmver%5B2%5D%26call%3Durl%5Bfile%3A%2Fproduct%2Fmain%5D"
                                ],
                                "v_still_life_image_base_url": [
                                    "https://image.hm.com/assets/hm/ed/57/ed578ed96f60439a308ff47279ffa2aff44fbd4e.jpg"
                                ],
                                "v_stock_state": [
                                    "true"
                                ],
                                "v_stylewith": [
                                    ""
                                ],
                                "v_swatch": [
                                    ""
                                ],
                                "v_turnToSku": [
                                    "1076691006004"
                                ],
                                "v_yellowprice": [
                                    "0.0"
                                ]
                            }
                        }
                    ],
                    "attributes": {
                        "age_gender_categories": [
                            "AdultoMujer"
                        ],
                        "age_groups": [
                            "Adulto"
                        ],
                        "all_article_base_images": [
                           
                        ],
                        "all_article_codes": [
                            "1076691006",
                            "1076691002",
                            "1076691003",
                            "1076691004"
                        ],
                        "all_article_images": [
                        
                        ],
                        "all_categories_codes": [
                            
                        ],
                        "article_codes": [
                           
                        ],
                        "article_color_names": [
                            "Negro,Beige claro,Beige,White"
                        ],
                        "article_group_id": [
                            "1076691_group_006"
                        ],
                        "assortment_type": [
                            "Calzado"
                        ],
                        "brandID": [
                            "0"
                        ],
                        "brand_name": [
                            "H&M"
                        ],
                        "categories_names": [
                            "Ladies"
                        ],
                        "category_id": [
                            "/1/ladies/ladies_shoes/ladies_shoes_boots"
                        ],
                        "category_path": [
                            
                            "/1/ladies/ladies_divided/ladies_divided_shoes"
                        ],
                        "coming_soon": [
                            "false"
                        ],
                        "currency_iso": [
                            "MXN"
                        ],
                        "currency_symbol": [
                            "$"
                        ],
                        "customer_groups": [
                            "Mujer"
                        ],
                        "default_article": [
                            "1076691006"
                        ],
                        "department_categories_codes": [
                            "ladies_all"
                        ],
                        "external": [
                            "false"
                        ],
                        "features": [],
                        "folder_rankings": [
                            ""
                        ],
                        "footwear_styles": [
                            "Botas"
                        ],
                        "formatted_price": [
                            "$1,699.00"
                        ],
                        "heel_heights": [
                            "Plano"
                        ],
                        "hero_rankings": [
                            ""
                        ],
                        "is_new": [
                            "false"
                        ],
                        "is_on_sale": [
                            "false"
                        ],
                        "link_pdp": [
                            "/es_mx/productpage.1076691006.html"
                        ],
                        "main_category_code": [
                            "ladies_shoes_boots"
                        ],
                        "market_locale": [
                            "es_mx"
                        ],
                        "new_from": [
                            "2023/08/07"
                        ],
                        "origin": [
                            "hybris"
                        ],
                        "palette": [
                            "false"
                        ],
                        "presentation_product_types": [
                            "Zapatos"
                        ],
                        "price": [
                            "1699.0"
                        ],
                        "product_id": [
                            "1076691"
                        ],
                        "product_marker": [
                            ""
                        ],
                        "product_marker_colors": [
                            ""
                        ],
                        "product_marker_text": [
                            ""
                        ],
                        "product_name": [
                            "Botas a la rodilla"
                        ],
                        "product_pk": [
                            "9502744903681"
                        ],
                        "qualities": [],
                        "rgb_colors": [
                            "#272628,#D1BEA0,#9E8765,#EEEDE4"
                        ],
                        "shop_now_link": [
                            "/es_mx/productpage/_jcr_content/product.quickbuy.1076691006.html"
                        ],
                        "stock_amount": [
                            "1"
                        ],
                        "swatches": [],
                        "swatches_total": [
                            "4"
                        ],
                        "travel_size": [
                            "false"
                        ]
                    }
                }
             
            ]
        }
    ],
    "topSearches": [
        {
            "name": "top-searches",
            "ticket": "Oy9zbHAvdG9wLXNlYXJjaGVzOyM7IzsjOyM7IzsjOyM7",
            "path": "/slp/top-searches",
            "description": "Lists the most popular searches.",
            "displayName": "Top Searches",
            "attributes": {},
            "resultType": "phrases",
            "phrases": []
        }
    ],
    "didYouMean": [
        {
            "name": "did-you-mean",
            "ticket": "Oy9zbHAvZGlkLXlvdS1tZWFuOyM7IzsjOyM7IzsjOyM7",
            "path": "/slp/did-you-mean",
            "description": "Suggests spelling-corrected search phrases.",
            "displayName": "Did you mean",
            "attributes": {},
            "resultType": "corrections",
            "corrections": []
        }
    ]
}
```
La búsqueda es una respuesta a una base de datos de vectores donde se está tomando en cuenta la relevancia
de los elementos de las frases que contiene zapatos por ejemplo: zapatos, zapatos sin talón, zapatos mule, zapatos derby.

Con esta relevancia se esta tomando resultados por vectores y regresa el listado que se muestra en la imagen que se agrega aquí

Incluye todos los elementos de cada uno de los productos que se van mostrando como colores, tallas, precios, atributos, imagenes.
