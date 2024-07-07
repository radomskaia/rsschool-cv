# Alena Radomskaia

## Contact Information

- [**Telegram**](https://t.me/ARadomskaia)
- [**Discord**](https://discordapp.com/users/1005407603268010075): @aradomskaia

## About Me

I aspire to become a Front-end developer because I enjoy creating new things and seeing visual results. Though I am at
the beginning of my journey, I am passionate about learning and discovering new things every day. My strengths lie in my
enthusiasm for development and my commitment to continual growth and improvement.

## Skills

- **Languages**: HTML, CSS5, Sass, Git

## Code Examples

### HTML

```html
<div class="card">
    <div class="card__side card__side--front">
        <figure class="card-picture" aria-label="picture-1"></figure>
        <h4 class="card__heading"><span class="card__heading-span">The Sea Explorer</span></h4>
        <div class="card__details">
            <ul>
                <li>3 day tours</li>
                <li>Up to 30 people</li>
                <li>2 tour guides</li>
                <li>Sleep in cozy hotels</li>
                <li>Difficulty: easy</li>
            </ul>
        </div>
    </div>
    <div class="card__side card__side--back">
        <div class="card__price-box">
            <p class="card__price-box_only">Only</p>
            <p class="card__price-box_value">$497</p>
        </div>
        <a href="#popup" class="btn btn--white">Book now!</a>
    </div>
</div>
```

### CSS
```css
.card {
    height: 52rem;
    width: 100%;
    position: relative;
    perspective: 150rem;
    -webkit-perspective: 150rem;
}

.card-picture,
.card__side--back {
    background-image: linear-gradient(to right bottom, #ffb900, #ff7730), url(../img/nat-5.jpg);
    background-size: cover;
    background-position: top;
    }

.card__heading-span {
    background-image: linear-gradient(to right bottom, rgba(255, 185, 0, 0.85), rgba(255, 119, 48, 0.85));
    background-size: cover;
    background-position: top;
}

    .card-picture {
    height: 23rem;
    background-blend-mode: screen;
    clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
}

.card__heading {
    font-size: 2.8rem;
    font-weight: 300;
    text-transform: uppercase;
    color: #ffffff;
    text-align: right;
    width: 75%;
    position: absolute;
    top: 12rem;
    right: 2rem;
}

.card__heading-span {
    padding: 1rem 1.5rem;
    box-decoration-break: clone;
    -webkit-box-decoration-break: clone;
}

.card__details {
    padding: 3rem;
}

.card__details ul {
    list-style: none;
    width: 80%;
    margin: 0 auto;
}

.card__details ul li {
    padding: 1rem;
    border-bottom: 1px solid #eeeeee;
}
    
.card__side {
    border-radius: 3px;
    overflow: hidden;
    text-align:center;
    height: 100%;
    width: 100%;
    transition: all .8s ease;
    position: absolute;
    top: 0;
    left: 0;
    backface-visibility: hidden;
    box-shadow: 0 1.5rem 4rem rgba(0, 0, 0, 0.15);
}

.card__side--back {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 8rem;
    height: 100%;
    transform: rotateY(180deg);
}

.card__price-box {
    color: #ffffff;
    text-transform: uppercase;
}

.card__price-box_value {
    font-size: 6rem;
    font-weight: 100;
}
    
.card:hover .card__side--front {
    transform: rotateY(-180deg);
}

.card:hover .card__side--back {
    transform: rotateY(0deg);
}

```

### Sass

```scss
@mixin background-gradient($color_1, $color_2, $url:null, $dir: right bottom) {
  @if $url == null {
    background-image: linear-gradient(to #{$dir}, #{$color_1}, #{$color_2});
  } @else {
    background-image: linear-gradient(to #{$dir}, #{$color_1}, #{$color_2}), url(#{$url});
  }
  background-size: cover;
  background-position: top;
}

@mixin respond($breakpoint) {
  @if $breakpoint == phone {
    @media only screen and (max-width: 37.5em) {
      @content
    }
    //600px
  }

  @if $breakpoint == tab-port {
    @media only screen and (max-width: 56.25em) {
      @content
    }
    // 900px
  }

  @if $breakpoint == tab-land {
    @media only screen and (max-width: 75em) {
      @content
    }
    // 1200px
  }

  @if $breakpoint == big-desktop {
    @media only screen and (min-width: 112.5em) {
      @content
    }
    // 1800px
  }
}
```

## Experience

### Academic Projects

- **Omnifood
  **: [GitHub Repository](https://github.com/radomskaia/omnifood) [Demo](https://omnifood-aradomskaia.netlify.app/)
    - Technologies: HTML, CSS
- **Natours
  **: [GitHub Repository](https://github.com/radomskaia/natours) [Demo](https://natours-aradomskaia.netlify.app/)
    - Technologies: HTML, Sass

## Education

- **Codecademy**
    - [Learn HTML](https://www.codecademy.com/enrolled/courses/learn-html)
    - [Learn CSS](https://www.codecademy.com/enrolled/courses/learn-css)
    - [Learn Intermediate CSS](https://www.codecademy.com/enrolled/courses/learn-intermediate-css)
    - [Learn Sass](https://www.codecademy.com/enrolled/courses/learn-sass)
- **Udemy**
    - [Build Responsive Real-World Websites with HTML and CSS](https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3/?couponCode=LETSLEARNNOW)
      by Jonas Schmedtmann
    - [Advanced CSS and Sass](https://www.udemy.com/course/advanced-css-and-sass/?couponCode=ST19MT61724) by Jonas
      Schmedtmann

## Languages

- **Russian**: Native
- **English**: B1
