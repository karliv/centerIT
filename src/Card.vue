<template>
    <section class="main-content__item">
        <div class="test-line">
            <div class="main-content__item-tag">
                <a href="#" class="main-content__tag-link text-style_sm">полнометражный фильм</a>
                <div class="dropdown-menu__icon">
                                    <span class="svg-icon">
                                    <svg class="svg-icon" xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                                         fill="none" viewBox="0 0 16 16">
                                        <path fill="#808792" fill-rule="evenodd"
                                              d="M4 8a2 2 0 1 1-4 0 2 2 0 0 1 4 0zm6 0a2 2 0 1 1-4 0 2 2 0 0 1 4 0zm4 2a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"
                                              clip-rule="evenodd"></path>
                                    </svg>
                                </span>
                    <div class="dropdown-menu">
                        <ul>
                            <li><a href="#" class="text-style_md">В архив</a></li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="main-content__item-title bd-line">
                <h6 class="text-style_lg">Требуется актер на роль самца в новом фильме</h6>
                <div class="ad-tags">
                    <span class="text-style_md-2">Актер, Модель</span>
                    <span class="text-style_md-2">Мужской</span>
                    <span class="text-style_md-2">20-24</span>
                </div>
            </div>
            <div class="main-content__item-descr bd-line">
                <p>Дата кастинга:<span class="text-style_md-2">20.06.19 – 30.06.19</span></p>
                <p>Дата кастинга:<span class="text-style_md-2">20.06.19 – 30.06.19</span></p>
                <span class="text-style_lg">1 400 000 ₽</span>
            </div>
            <div class="main-content__item-btn">
                <span class="text-style_md" v-if="!isRespond" @click="showModal">откликнуться</span>
                <span class="text-style_md disabled" v-else>отклик отправлен</span>
            </div>
        </div>
        <Alert v-if="isModalVisible" :onResponded="onResponded" :closeModal="closeModal"/>
    </section>
</template>

<script>
    import Alert from './Alert';

    export default {
        name: "Card",
        components: {Alert},
        props: ["openModel"],
        data() {
            return {
                count: 1,
                isModalVisible: false,
                isRespond: false
            }
        },
        methods: {
            showModal() {
                this.isModalVisible = true;
            },
            closeModal() {
                this.isModalVisible = false;
            },
            onResponded() {
                this.isRespond = true;
                this.isModalVisible = false
            }
        },
    }
</script>

<style scoped>

</style>