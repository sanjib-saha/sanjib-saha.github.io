<template>
  <div>
    <h1>This is a about page</h1>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
  head () {
    return {
      title: "NUXT || About || By Sanjib Kumar Saha",
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s"
        },
        {
          hid: 'og:title',
          name: 'og:title',
          content: "OG || NUXT || About || By Sanjib Kumar Saha"
        },
        {
          hid: 'og:image',
          name: 'og:image',
          // content: "https://demo.sirv.com/chair.jpg"
          content: "https://orkoweb.services/storage/images/profile/Orko-Pro_2022_12_21_20_59_33-Dec-21st-22-8-59-43.jpg"
        }
      ]
    }
  }
}
</script>
