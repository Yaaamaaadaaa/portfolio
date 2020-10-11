<template>
  <section
    id="welcome"
    class="overflow-hidden"
  >
    <v-row no-gutters>
      <v-col
        class="hidden-sm-and-down"
        md="6"
      >
        <v-img
          :src="require('@/assets/welcome.png')"
          height="100vh"
        />
      </v-col>

      <v-col
        class="align-content-space-between layout wrap"
        cols="12"
        md="6"
        :pa-5="$vuetify.breakpoint.smAndDown"
      >
        <base-bubble-1
          style="transform: rotate(180deg) translateY(25%)"
        />

        <v-row
          align="center"
          justify="center"
        >
          <v-col
            cols="10"
            md="6"
          >
            <h1>自己紹介</h1>
            <p>
              山田翔太と申します。私は1年6ヶ月間、土木関係資材を扱う商社で営業を担当していました。<br>
              今回はエンジニアという異業種へのチャレンジですが、
              提案力・信頼関係を構築する能力を磨いてきましたので、この経験を生かして、御社では相手の目線で考えられ、
              必要とされるものを判断でき、決断力のあるエンジニアになりたいと考えております。
            </p>
          </v-col>
        </v-row>

        <base-bubble-2
          style="transform: rotate(180deg) translate(-200px, -15%)"
        />
      </v-col>
    </v-row>
  </section>
</template>
