# Olga Fedorovich
## Junior Frontend Developer

### PERSONAL SUMMARY: 
I'm an enthusiastic and detail-oriented Frontend Developer seeking an entry-level position with Company to use my skills in coding, troubleshooting complex problems, and assisting in the timely completion of projects.

### Contact:
* **Contact phone:** +375 29 507 65 63
* **Email:** fedola@mail.ru
* Minsk, Belarus
* **Social media:**
[Facebook](https://www.facebook.com/profile.php?id=1837378495)
[Instagram](https://www.instagram.com/fedorovich_olya/)

### Skills:
* Javascript/ES5/ES6
* Angular + NGRX
* HTML/CSS
* Node.JS/Express/KOA
* Bootstrap/JQUERY

### Code examples:
```
        const createCard = function(cardIndex) {
            let imageName = cardsArray[cardIndex];
            let card = document.createElement('div');
            card.classList.add('card');
            card.dataset.name = imageName;

            card.innerHTML = `
                <div class="card_item card_upper_side" style="background: url(img/upper-card.jpg); background-size: 100% auto; background-position-y: 50%" ></div>
                <div class = "card_item card_down_side" style="background: url(img/${imageName}.jpg); background-size: auto 100%; background-position-x: 50%"></div>
            `;
            playingSpace.appendChild(card);
        };

        for(let i = 1; i <= 18; i++) {
            const getRandomCard = function(min, max) {
                return Math.random() * (max - min) + min;
            };
            let cardIndex = parseInt(getRandomCard(0, cardsArrayLength-1));
            createCard(cardIndex);
            cardsArray.splice(cardIndex, 1);
            cardsArrayLength = cardsArray.length;
        }
```