<template lang="pug">
  footer
    .footer
      .container
        .footer-grid
          .contacts Контакты
            .contacts-list
              .contacts-item
                a(href='tel:+79536802511' target="_blank").buy-info__link
                  .contacts-item--svg
                    img(src='@/assets/image/phone.svg')
                  .buy-info__pdf-title +79536802511
                a(href='https://ig.clck.bar/butorinanesty' target="_blank").buy-info__link
                  .contacts-item--svg
                    img(src='@/assets/image/instagram.svg')
                  .buy-info__pdf-title Instagram
                a(href='https://t.me/+79536802511' target="_blank").buy-info__link
                  .contacts-item--svg
                    img(src='@/assets/image/telegram.svg')
                  .buy-info__pdf-title Telegram
                a(href='https://wa.me/79536802511' target="_blank").buy-info__link
                  .contacts-item--svg
                    img(src='@/assets/image/whatsapp.svg')
                  .buy-info__pdf-title Whatsapp

          .buy-info
            .buy-info__documents
              .buy-info__item
                a(href='#').buy-info__link
                  .buy-info__pdf
                    img(src='@/assets/image/placeholder-for-pdf.png')
                  .buy-info__pdf-title Договор-офера оказания медицинских услуг
              .buy-info__item
                a(href='#').buy-info__link
                  .buy-info__pdf
                    img(src='@/assets/image/placeholder-for-pdf.png')
                  .buy-info__pdf-title Договор-офера оказания каких то других услуг
            .buy-info__contacts Платежная информация
              .buy-info__contacts-item БИК: 010101010
              .buy-info__contacts-item ВИК: 984984894
              .buy-info__contacts-item СПБ: +79274238025 (Сбер)
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>

</style>
