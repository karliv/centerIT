<template>
    <transition name="modal-fade">
        <div class="modal-bg" role="dialog">
            <div class="modal-wrapper">
                <div class="modal-container" ref="modal">
                    <div class="modal__img">
                        <svg xmlns="http://www.w3.org/2000/svg" width="64" height="64" fill="none" viewBox="0 0 64 64">
                            <path fill="#0063DA" fill-rule="evenodd"
                                  d="M2.8 18.06l56-16c2.8-.4 5.2 1.2 5.2 4v47.6c0 2.8-2.8 4.8-5.2 4L36 51.26v6.8c0 2.4-1.6 4-4 4H12c-2.4 0-4-1.6-4-4v-14.8l-5.2-1.2c-1.6-.8-2.8-2.4-2.8-4v-16c0-1.6 1.2-3.2 2.8-4zm13.2 36h12v-4.8l-12-3.6v8.4z"
                                  clip-rule="evenodd"></path>
                        </svg>
                    </div>
                    <div class="modal__title">
                        Отклик на кастинг
                    </div>
                    <p class="modal__descr">
                        Название кастинга, которое умещается в 2 строки
                    </p>
                    <button class="btn-style btn-main text-style_md" @click="onResponded">
                        отправить
                    </button>
                    <button class="btn-style btn-close" @click="closeModal" aria-label="Close modal">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none" viewBox="0 0 16 16">
                            <path fill="#fff" fill-opacity=".64"
                                  d="M10.467 3.766L7.995 6.238 5.59 3.834c-.424-.425-.99-.425-1.413-.001l-.283.282c-.423.424-.423.99.001 1.414L6.3 7.933l-2.472 2.472c-.423.424-.423.99.001 1.413l.354.354c.424.424.99.425 1.413 0l2.402-2.4 2.404 2.403c.424.425.99.425 1.413.001l.353-.353c.424-.424.424-.989 0-1.413L9.691 7.935l2.401-2.402c.424-.423.424-.989 0-1.413l-.284-.283c-.353-.495-.99-.424-1.342-.071z"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
    </transition>
</template>

<script>
    export default {
        name: "Alert",
        props: ["closeModal", "onResponded"],
    }
</script>

<style scoped>

</style>