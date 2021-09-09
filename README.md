# assaignment2-gadiparthi
# SAI KRISHNA GADIPATHRI
###### GOA
>Goa is a state in **western** India with coastlines stretching along the Arabian Sea. Its long history as a Portuguese colony prior to 1961 is evident in its preserved 17th-century churches and the area’s tropical spice plantations. **Goa is also known for its beaches, ranging from popular stretches at Baga and Palolem to those in laid-back fishing villages such as Agonda**

#### Travel Guid

---


1. Goa is a Best place in india and there is a  so many beaches its looks Beautiful there is a games also in ships the game name is casino there are so many things to see 
    1. there is a best hotels in Goa 
2.  We plan your perfect Holiday in Goa,
    1. First we take a car and go to Google map and search a route map on Goa 
3.  In Goa beears are very cheep
    1. The cost of the bear is 40 RS
4. there is very cool climate
    * wether is always cool and sum times there is a rain falling
    * food ietms
    * Rotis
    * Butternons
    * Biryanis
5. the cost of trip is nearly 20000
    * we can perfer for trip to vechils like
    * Cars
    * Trains
    * Planes

[About me file](AboutMe.md)

The following table describes the 4 types of food/drinks that everyone should try.<br>
It describes the food/drink item name, location and amount of money.
 
### FOOD & Drink Table
 
---
 
| Food/Drink Item | Location | Amount |
|   ----------    |  -----   |   ---- | 
| chapathi | Hyderabad | $75 |
| stella Extra | Texas | $90 |
|BBQ | BBQ Nation| $10 |
| biryani | Vijayawada ST food | $20 |

### Pithy Quotes

---

## Quotes

> "Don't judge each day by the harvest you reap but by the seeds that you plant"
>> -*robert [lous stevenson]* <br>
> "Friend is a gift you give yourself"
>> -*robert lous stevenson*

## code fencing

---

If the distance is less than the radius, the line must intersect the circle at two distinct points. if the distance is equal to the radius, then the line will touch the circle. if the distance is greater than the radius, the line will lie completely outside the circle.

```
double r, a, b, c; // given as input
double x0 = -a*c/(a*a+b*b), y0 = -b*c/(a*a+b*b);
if (c*c > r*r*(a*a+b*b)+EPS)
    puts ("no points");
else if (abs (c*c - r*r*(a*a+b*b)) < EPS) {
    puts ("1 point");
    cout << x0 << ' ' << y0 << '\n';
}
else {
    double d = r*r - c*c/(a*a+b*b);
    double mult = sqrt (d / (a*a+b*b));
    double ax, ay, bx, by;
    ax = x0 + b * mult;
    bx = x0 - b * mult;
    ay = y0 - a * mult;
    by = y0 + a * mult;
    puts ("2 points");
    cout << ax << ' ' << ay << '\n' << bx << ' ' << by << '\n';
}
```

https://doubleroot.in/lessons/circle/intersection-line-circle-1/#:~:text=if%20the%20distance%20is%20less,lie%20completely%20outside%20the%20circle.