## Человек__голова

### Человек__глаз
### Человек__глаз--закрыт
### Человек__нос
### Человек__нос--дышит
### Человек__ухо
### Человек__ухо--слышит
### Человек__рот
### Человек__рот--открыт

## Человек__тело
### Человек__печень
### Человек__печень--очищает
### Человек__сердце
### Человек__сердце--стучит
### Человек__почка
### Человек__почка--фильтрует
### Человек__желудок
### Человек__желудок--переваривает

## Человек__рука
### Человек__ладонь
#### Человек__палец
#### Человек__палец--согнут
### Человек__предпелчье
### Человек__предпелчье--напряжено
### Человек__плечо
### Человек__плечо--вывихнуто
### Человек__кисть
### Человек__кисть--согнута

## Человек__нога
### Человек ступня
#### Человек__палец
#### Человек__палец--согнут


## Макет

### header
![хедер макета](/img/header.png)
```
    header.header>(a.header>img.header)+nav>(ul.header>(li.header>a)*7)
```
![форма макета](/img/form.png)
```
    section.section0>div.wrapper>(div.left>h1+p+(form.section0>(label>span+input.section0)+button.section0))+img.section0
```
![карточки макета](/img/card.png)
```
    section.section5>div.wrapper>h2.section2+(ul.section5>(li>img+h2+p+time)*3)+a.section5
```
![футер макета](/img/footer.png)
```
    footer>section>div>img+(div>h3+ul>(li>a)*8)+(div>h3+ul>(li>a)*4)+(div>h3+ul>(li>a)*2)
```