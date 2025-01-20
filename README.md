# living expenses data

## objective

Bu loyiha odamning bir oy ichida yashash xarajatlarini hisoblash uchun mo‘ljallangan.

## data

```json
{
    "rent": 1200, 
    "utilities": 300, 
    "transport": 450, 
    "food": 600, 
    "entertainment": 110, 
    "clothing": 220, 
    "health": 30, 
    "internet": 60, 
    "education": 200, 
    "other": 100
}
```
- rent: oylik ijara
- utilities: oylik kommunal xizmatlar
- transport: oylik transport
- food: oylik oziq-ovqat
- entertainment: oylik ko‘ngilochar harajatlar
- clothing: oylik kiyim-kechak
- health: oylik sog‘liqni saqlash
- internet: oylik internet
- education: oylik ta'lim
- other: boshqa oylik xarajatlar

## functions

- `get_data`: json fayldan ma'lumotlarni olish
- `total_expenses`: odamning bir oy ichidagi umumiy xarajatlarini hisoblash
- `average_expenses`: odamning bir oy ichidagi o‘rtacha xarajatlarini hisoblash
- `the_most_expensive`: odamning bir oy ichidagi eng qimmat xarajatlarini hisoblash
- `the_least_expensive`: odamning bir oy ichidagi eng arzon xarajatlarini hisoblash
