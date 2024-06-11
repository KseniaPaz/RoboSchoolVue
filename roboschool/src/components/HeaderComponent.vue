<template>
    <div>
        <header class="header center">
            <div class="header__head">
                <a class="logo" href="index.html">ROBO.SCHOOL</a>
                <nav class="menu">
                    <a href="#section_info" class="menu__link">О школе</a>
                    <a href="#section_teachers" class="menu__link">Тренеры</a>
                    <a href="#section_price" class="menu__link">Стоимость</a>
                </nav>
                <p class="phone-number">+7 800 000 11 22</p>
            </div>
            <div class="top">
                <div class="top__left">
                    <h1 class="top__left__title">ROBO SCHOOL</h1>
                    <p class="top__left__text">Курсы повышения квалификации по робототехнике для педагогов начальной школы
                    </p>
                    <a href="#section_subscribe" class="top__left__button">Записаться на курс</a>
                </div>
                <div class="top__right"><img class="top__img" src="img/Top-image.png" alt="top__img"></div>
            </div>
        </header>
    </div>
</template>

<script>
export default {
    name: 'HeaderComponent',
}
</script>