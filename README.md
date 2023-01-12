# Hankeen nimi
Tähän hankeen rahoittajien logot

# Markdown ohjeita
[Extended syntax] https://www.markdownguide.org/extended-syntax/

# Ohjelmakoodin lisääminen

- Koodin upotuslaatikko
~~~python
# Esimerkkikoodi Pythonilla

def gcd_iter(u, v):
    while v:
        u, v = v, u % v
    return abs(u)
~~~~

~~~javascript
// Esimerkkikoodi JavaScriptillä
function gcd_rec(a, b) {
  return b ? gcd_rec(b, a % b) : Math.abs(a);
}
~~~



