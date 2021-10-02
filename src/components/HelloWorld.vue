<template>
  <v-container>
    <v-row class="text-center" >
      <v-card
        v-for="(item, index) in items"
        class="mx-auto mt-3"
        color="#26c6da"
        dark
        max-width="400"
        :key="index"
      >
        <v-card-title>
          <v-icon
            large
            left
          >
            mdi-twitter
          </v-icon>
          <span class="text-h6 font-weight-light">{{item.title}}</span>
        </v-card-title>

        <v-card-text class="text-h5 font-weight-bold">
         {{item.sentence}}
        </v-card-text>

        <v-card-actions>
          <v-list-item class="grow">
            <v-list-item-avatar color="grey darken-3">
              <v-img
                class="elevation-6"
                alt=""
                :src="item.link"
              ></v-img>
            </v-list-item-avatar>

            <v-list-item-content>
              <v-list-item-title>{{item.name}}</v-list-item-title>
            </v-list-item-content>

            <v-row
              align="center"
              justify="end"
            >
              <v-icon class="mr-1">
                mdi-heart
              </v-icon>
              <span class="subheading mr-2">256</span>
              <span class="mr-1">·</span>
              <v-icon class="mr-1">
                mdi-share-variant
              </v-icon>
              <span class="subheading">45</span>
            </v-row>
          </v-list-item>
        </v-card-actions>
      </v-card>  
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      items:[
        {
          name: 'Fabio',
          sentence: 'Soy Fabio Zapata, me acabo de graduar. tengo 23 años y me gusta programar Web (Back)', 
          title: 'prueba 1',
          link: 'https://cdn3.iconfinder.com/data/icons/avatars-flat/33/man_5-512.png',
        },
        {
          name: 'Miguel Nieto A',
          sentence: 'Soy Miguel Nieto A, estudiante de octavo semestre. Me gusta el desarrollo backend y la analítica de datos. Aprendiendo Ruby! 😎', 
          title: 'Contribution from Miguel!',
          link: 'https://img2.freepng.es/20180623/iqh/kisspng-computer-icons-avatar-social-media-blog-font-aweso-avatar-icon-5b2e99c40ce333.6524068515297806760528.jpg',
        },
      ]
    }),
  }
</script>
