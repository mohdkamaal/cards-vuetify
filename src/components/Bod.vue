<template>
  <v-container fluid>
    <v-layout row class="parent pa-5 ml-5 mr-5 mt-5">
      <v-flex>
        <v-card
          class="bt mb-4 pa-2 text-center"
          max-width="100px"
          tile
          color="purple darken-1"
          dark
        >CLASS 1</v-card>
        <v-card class="mr-3">
          <v-card-text>
            <v-col cols="auto">
              <div>
                <p class="headline">Section A</p>
              </div>
              <v-divider></v-divider>
              <v-img
                height="100"
                width="100"
                src="https://cdn.vuetifyjs.com/images/cards/store.jpg"
              ></v-img>
            </v-col>
          </v-card-text>
        </v-card>
      </v-flex>
      <v-flex>
        <v-card class="mr-3 mt-4">
          <v-card-text>
            <v-col cols="auto">
              <p class="headline">Section B</p>
              <v-divider></v-divider>
              <v-img
                height="100"
                width="100"
                src="https://cdn.vuetifyjs.com/images/cards/store.jpg"
              ></v-img>
            </v-col>
          </v-card-text>
        </v-card>
      </v-flex>
      <v-flex>
        <v-card class="mr-3 mt-4">
          <v-card-text>
            <v-col cols="auto">
              <p class="headline">Section C</p>
              <v-divider></v-divider>
              <v-img
                height="100"
                width="100"
                src="https://cdn.vuetifyjs.com/images/cards/store.jpg"
              ></v-img>
            </v-col>
          </v-card-text>
        </v-card>
      </v-flex>
      <v-flex>
        <v-card class="mr-3 mt-4">
          <v-card-text>
            <v-col cols="auto">
              <p class="headline">Section D</p>
              <v-divider></v-divider>
              <v-img
                height="100"
                width="100"
                src="https://cdn.vuetifyjs.com/images/cards/store.jpg"
              ></v-img>
            </v-col>
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
    <v-layout row class="parent pa-5 ml-5 mr-5 mt-5">
      <v-flex>
        <v-card
          class="bt mb-4 pa-2 text-center"
          max-width="100px"
          tile
          color="purple darken-1"
          dark
        >CLASS 2</v-card>
        <v-card class="mr-3">
          <v-card-text>
            <v-col cols="auto">
              <p class="headline">Section A</p>
              <v-divider></v-divider>
              <v-img
                height="100"
                width="100"
                src="https://cdn.vuetifyjs.com/images/cards/store.jpg"
              ></v-img>
            </v-col>
          </v-card-text>
        </v-card>
      </v-flex>
      <v-flex>
        <v-card class="mr-3 mt-4">
          <v-card-text>
            <v-col cols="auto">
              <p class="headline">Section B</p>
              <v-divider></v-divider>
              <v-img
                height="100"
                width="100"
                src="https://cdn.vuetifyjs.com/images/cards/store.jpg"
              ></v-img>
            </v-col>
          </v-card-text>
        </v-card>
      </v-flex>
      <v-flex>
        <v-card class="mr-3 mt-4">
          <v-card-text>
            <v-col cols="auto">
              <p class="headline">Section C</p>
              <v-divider></v-divider>
              <v-img
                height="100"
                width="100"
                src="https://cdn.vuetifyjs.com/images/cards/store.jpg"
              ></v-img>
            </v-col>
          </v-card-text>
        </v-card>
      </v-flex>
      <v-flex>
        <v-card class="mr-3 mt-4">
          <v-card-text>
            <v-col cols="auto">
              <p class="headline">Section D</p>
              <v-divider></v-divider>
              <v-img
                height="100"
                width="100"
                src="https://cdn.vuetifyjs.com/images/cards/store.jpg"
              ></v-img>
            </v-col>
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>
<script>
export default {
  name: "class"
};
</script>
 <style lang="scss" scoped>
.parent {
  border: 3px solid #6A1B9A;
  position: relative;
}
.bt {
  margin-top: -40px;
}
</style>