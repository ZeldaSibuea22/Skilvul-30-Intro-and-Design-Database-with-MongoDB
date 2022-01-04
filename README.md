# Skilvul-30-Intro-and-Design-Database-with-MongoDB

## Soal nomor 1
### Profile Skiljek

```js
{
"_id": "ObjectId('ABC')",
"full_name": "Zelda Elma Sibuea",
"email": "zelda.sibuea43@gmail.com",
"phone_number": 0858********
}
```

## Soal nomor 2 Profile Skilshop
<h2>Relasi one to many</h2>

```js
{
    "_id": "ObjectId('CBA')",
    "full_name": "Zelda Elma Sibuea",
    "phone_mumber": 0858********
    "address": [
        "ObjectId('XYZ')",
        "ObjectId('LMN')",
    ]
}
```

## Soal nomor 3
<h2>Relasi one to one</h2>

```js
{
    "_id": "ObjectId('ABA')",
    "product_name": "Laptop",
    "brand_name": "SkilShirt",
    "variant": [{
        "_id": "ObjectId('BAB')",
        "variant_name_1": "Laptop Asus",
        "color": "Hitam",
        "quantity": 12,
        "price": "Rp 140.000",
    },{
         "_id": "ObjectId('CAC')",
        "variant_name_2": "Laptop Acer",
        "color": "Navy",
        "quantity": 10,
        "price": "Rp 150.000",
    }]
}
```

## Soal nomor 4
<h2>Relasi one to many</h2>

```js
[
    {
    "_id": "ObjectId('SKV')",
    "cinema_name": "Monsta",
    "film": [
        "ObjectId('Harry Potter')",
        "ObjectId('Harry Potter 2')"
    ],
    "location": "Medan"
    },
    {
    "_id": "ObjectId('VKS')",
    "cinema_name": "Cinema 31",
    "film": [
        "ObjectId('Avenger')",
        "ObjectId('Spiderman')"
    ],
     "location": "Medan"
    }
]
```
