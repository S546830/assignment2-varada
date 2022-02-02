# assignment2-varada
# Varada Sai Malayaja
#### Tondle is my favourite place to buy food

There is a **beach** side to this restaurant full of lights and decorations.There also be fishermen with sailing boats loading the live fishes caught from the beach into the restaurant.A mall named **Mayajaal** is infront of this beach which is famous for varieties of ceramic pots.

-------------------------------------------------------------------------------

# Chennai International Airport
### Chennai International Airport is the closest airport to this food location
1. Chennai International Airport
2. Head northeast on Service Rd toward Airport Terminal Link
3. Turn left toward Airport Terminal Link
4. Continue straight onto Kalaignar aKarunanidhi Salai
5. Use the right 2 lanes to turn right onto East Coast Rd
6. Tondle the family restaurants

### Specific Food Items

* Royal prawns kabab
* Malai kofta
* Steamed Crab

[Get To Know Meee](https://github.com/S546830/assignment2-varada/blob/main/AboutMe.md)

--------------------------------------------------------------------------------------------------------

# Sports  

| Name   |   Location   |   Amount   |
|--------|--------------|------------|
| Squash | omr road     | $30        |
| Tennis | ecr road     | $20        |
| Hockey | mgr road     | $35        |

--------------------------------------------------------------------------------------------------------

# Quotations

>A little note of daily plans can make you so much better. *Kaushal Yadav*

>Confidence is classy,Always wear it. *Ricky Meher*

---------------------------------------------------------------------------------------------------------

# Geometry  Elementary

>Basic geometry is the study of points, lines, angles, surfaces, and solids.The study of this topic starts with an understanding of these. Let's define them.

Elaboration (https://www.basic-mathematics.com/basic-geometry.html)

        struct point2d {
        ftype x, y;
        point2d() {}
        point2d(ftype x, ftype y): x(x), y(y) {}
        point2d& operator+=(const point2d &t) {
            x += t.x;
            y += t.y;
            return *this;
        }
        point2d& operator-=(const point2d &t) {
            x -= t.x;
            y -= t.y;
            return *this;
        }
        point2d& operator*=(ftype t) {
            x *= t;
            y *= t;
            return *this;
        }
        point2d& operator/=(ftype t) {
            x /= t;
            y /= t;
            return *this;
        }
        point2d operator+(const point2d &t) const {
            return point2d(*this) += t;
        }
        point2d operator-(const point2d &t) const {
            return point2d(*this) -= t;
        }
        point2d operator*(ftype t) const {
            return point2d(*this) *= t;
        }
        point2d operator/(ftype t) const {
            return point2d(*this) /= t;
        }
    };
    point2d operator*(ftype a, point2d b) {
        return b * a;
    }

Extended Information (https://cp-algorithms.com/geometry/basic-geometry.html)