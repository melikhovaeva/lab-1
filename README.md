# BEM
 Github Branching Workout

## Человеческое тело BEM

### Голова
```
.голова

.голова__глаз
.голова__нос
.голова__губы

.голова__глаз--линза_черная
.голова__нос--пирсинг
.голова__губы--помада_красная
```
### Рука

```
.рука

.рука__локоть
.рука__палец
.рука__кисть

.рука__локоть--с_раной
.рука__палец--ногти_красные
```
### Тело

```
.тело

.тело__грудь

.тело__грудь--татуировка
```

## BEM на примере проекта. Вариант 10

![Header](img/header.jpg)

```
header.header>(a.header__logo.logo>img.logo__img)+(nav.header__navigation.navigation>a.navigation__link)+p.header__contact
```
![Card](img/card.jpg)

```
section.advantages>ul.advantages__list*3>li.advantages__item>img.advantages__icon+h2.advantages__title+p.advantages__description
```

![Forma](img/forma.jpg)

```
section.feedback>form.feedback__forma>label.feedback__shell*4+input.feedback__submit+p.feedback__notice>input.feedback__input
```

![Footer](img/footer.jpg)

```
footer.footer>div.footer__wrapper>(a.footer__logo.logo>img.logo__img)+(ul.footer__list*3>li.footer__item*3)
```
