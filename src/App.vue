<template>
    <div id="app" class="wrapper">
        <header class="header">
            <div class="lg-container">
                <nav class="header-menu">
                    <div class="logo">
                        <img src="./assets/img/logo2.png" alt="Linkmuse">
                    </div>
                    <ul class="menu-list">
                        <li><a class="menu-list__link text-style_lg" href="#">Объявления</a></li>
                        <li><a class="menu-list__link text-style_lg" href="#">Таланты</a></li>
                        <li><a class="menu-list__link text-style_lg" href="#">Заказчики</a></li>
                        <li><a class="menu-list__link text-style_lg" href="#">Верификация</a></li>
                        <li class="menu-list__dropdown svg-icon">
                            <svg class="svg-icon" xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none"
                                 viewBox="0 0 16 16">
                                <path fill="#808792" fill-rule="evenodd"
                                      d="M4 8a2 2 0 1 1-4 0 2 2 0 0 1 4 0zm6 0a2 2 0 1 1-4 0 2 2 0 0 1 4 0zm4 2a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"
                                      clip-rule="evenodd"></path>
                            </svg>
                        </li>
                    </ul>
                </nav>
                <div class="header-menu">
                    <ul class="menu-list profile">
                        <li>
                            <a class="menu-list__link menu-list__link_hover text-style_lg" href="">
                            <span class="menu-list__item-span">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none"
                                     viewBox="0 0 16 16"> <rect width="16" height="16" fill="#0063DA" rx="4"></rect>
                                    <path fill="#fff"
                                          d="M9 4.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v2a.5.5 0 0 1-.5.5h-2a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h2a.5.5 0 0 1 .5.5v2a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 1 .5-.5h2a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5h-2a.5.5 0 0 1-.5-.5v-2z"></path>
                                </svg>
                            </span> Создать
                            </a>
                        </li>
                        <li>
                            <div class="menu-list__item svg-icon">
                                <span class="menu-list__item-circle"></span>
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none"
                                     viewBox="0 0 16 16">
                                    <path fill="#808792"
                                          d="M8 0c4.4 0 8 3.1 8 7s-3.6 7-8 7c-.25 0-.502 0-.728-.025-.244-.026-.496-.022-.721.075l-3.157 1.353A1 1 0 0 1 2 14.483v-2.469c0-.265-.108-.517-.285-.715C.675 10.14 0 8.654 0 7c0-3.9 3.6-7 8-7z"></path>
                                </svg>
                            </div>
                        </li>
                        <li>
                            <div class="menu-list__item svg-icon">
                                <span class="menu-list__item-circle"></span>
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none"
                                     viewBox="0 0 16 16">
                                    <path fill="#808792"
                                          d="M10 14H6c0 1.1.9 2 2 2s2-.9 2-2zM15 11h-.5c-.7-.7-1.5-1.7-1.5-3V5c0-2.8-2.2-5-5-5S3 2.2 3 5v3c0 1.3-.8 2.3-1.5 3H1c-.6 0-1 .4-1 1s.4 1 1 1h14c.6 0 1-.4 1-1s-.4-1-1-1z"></path>
                                </svg>
                            </div>
                        </li>
                        <li>
                            <div class="menu-list__profile text-style_lg">
                                <img src="./assets/img/picha.png" class="menu-list__profile-img" alt="Profile Image">
                                Евгений
                                <span class="menu-list__profile-span svg-icon">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none"
                                     viewBox="0 0 16 16">
                                    <path fill="#808792"
                                          d="M8 10L4.5 6.824 5.407 6 8 8.353 10.593 6l.907.824L8 10z"></path>
                                </svg>
                            </span>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
        </header>
        <main class="main">
            <div class="lg-container">
                <div class="sidebar">
                    <div class="sidebar-profile wrapp-block">
                        <div class="sidebar-profile__img">
                            <img src="./assets/img/fake3.jpg" alt="">
                        </div>
                        <h3>Virginia Freeman</h3>
                        <h5 class="text-style_md">Агентство</h5>
                    </div>
                    <div class="sidebar-statistic wrapp-block">
                        <div class="sidebar-statistic__item">
                            <span class="text-style_lg">86</span>
                            <span class="text-style_sm">Подписок</span>
                        </div>
                        <div class="sidebar-statistic__border"></div>
                        <div class="sidebar-statistic__item">
                            <span class="text-style_lg">234</span>
                            <span class="text-style_sm">Подписчика</span>
                        </div>
                    </div>

                    <div class="sidebar-tasks wrapp-block">
                        <div class="sidebar-tasks__item">
                            <div class="sidebar-tasks__text">
                                <span class="text-style_lg">Сотрудничества</span>
                                <span class="text-style_md">24</span>
                            </div>
                            <div class="svg-icon">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none"
                                     viewBox="0 0 16 16">
                                    <path fill="#0063DA"
                                          d="M10.362 7.317a1 1 0 0 1 0 1.366L7.58 11.662a.752.752 0 0 1-1.1-1.027l1.824-1.952a1 1 0 0 0 0-1.366L6.48 5.365a.752.752 0 1 1 1.1-1.027l2.782 2.98z"></path>
                                </svg>
                            </div>
                        </div>
                        <div class="sidebar-tasks__item">
                            <div class="sidebar-tasks__text ">
                                <span class="text-style_lg">Отклики</span>
                                <span class="text-style_md">8</span>
                            </div>
                            <div class="svg-icon">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none"
                                     viewBox="0 0 16 16">
                                    <path fill="#0063DA"
                                          d="M10.362 7.317a1 1 0 0 1 0 1.366L7.58 11.662a.752.752 0 0 1-1.1-1.027l1.824-1.952a1 1 0 0 0 0-1.366L6.48 5.365a.752.752 0 1 1 1.1-1.027l2.782 2.98z"></path>
                                </svg>
                            </div>
                        </div>
                    </div>
                </div>
                <article class="main-content">
                    <div class="main-content__title wrapp-block">
                        <h5 class="text-style_md">Объявления</h5>
                    </div>
                    <div class="main-content__list wrapp-block">
                        <Card v-for="(card, i) in cards" :key="card.id" />
                    </div>
                </article>
            </div>
        </main>
    </div>
</template>

<script>
    import Card from './Card';

    export default {
        name: 'app',
        components: {Card},
        data() {
            return {
                cards: [
                    {id:1},
                    {id:2},
                    {id:3},
                ],
            }
        }
    }
</script>

<style lang="sass">

</style>
