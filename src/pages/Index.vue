<template>
  <q-page class="flex flex-center">
    <div class="q-pa-md">
      <div class="q-gutter-md row items-start">
        <q-card class="Card 001" style="width: 300px" q-mr-md>
          <q-card-section
            class="bg-red-11 text-white text-center text-weight-medium"
          >
            This is a Kirby Card ^-^
          </q-card-section>
          <img src="../assets/imagens/kirbybomb.jpg " />
          <q-card-section>
            Artwork of a green Kirby with the Bomb ability on the game Kirby
            Battle Royale.
          </q-card-section>
          <q-card-actions align="right">
            <q-btn flat round color="red-9" icon="favorite" />
            <q-btn flat round color="grey-4" icon="bookmark" />
            <q-btn flat round color="grey-4" icon="share" />
          </q-card-actions>
        </q-card>

        <q-card class="Card 002" style="width: 300px" q-mr-md>
          <q-card-section
            class="bg-red-11 text-white text-center text-weight-medium"
          >
            This is a Kirby Card ^-^
          </q-card-section>
          <img
            src="../assets/imagens/kirbymarreta.png "
            style="width: 400px; height: 233px"
            :fit="mode"
          />
          <q-card-section>
            Artwork of a green Kirby with the Hammer ability on the game Kirby
            Battle Royale.
          </q-card-section>
          <q-card-actions align="right">
            <q-btn flat round color="red-9" icon="favorite" />
            <q-btn flat round color="grey-4" icon="bookmark" />
            <q-btn flat round color="grey-4" icon="share" />
          </q-card-actions>
        </q-card>

        <q-card class="Card 003" style="width: 300px" q-mr-md>
          <q-card-section
            class="bg-red-11 text-white text-center text-weight-medium"
          >
            This is a Kirby Card ^-^
          </q-card-section>
          <img
            src="../assets/imagens/kirbyninja.jpg "
            style="width: 400px; height: 233px"
            :fit="mode"
          />
          <q-card-section>
            Artwork of a blue Kirby with the Ninja ability on the game Kirby
            Battle Royale.
          </q-card-section>
          <q-card-actions align="right">
            <q-btn flat round color="red-9" icon="favorite" />
            <q-btn flat round color="grey-4" icon="bookmark" />
            <q-btn flat round color="grey-4" icon="share" />
          </q-card-actions>
        </q-card>

        <q-card class="Card 004" style="width: 300px" q-mr-md>
          <q-card-section
            class="bg-red-11 text-white text-center text-weight-medium"
          >
            This is a Kirby Card ^-^
          </q-card-section>
          <img
            src="../assets/imagens/kirbyespada.png "
            style="width: 300px; height: 233px"
            :fit="mode"
          />
          <q-card-section>
            Artwork of the Sword ability on the game Kirby Battle Royale.
          </q-card-section>
          <q-card-actions align="right">
            <q-btn
              flat
              round
              color="red-9"
              icon="favorite"
              @click="handleClick"
            />
            <q-btn flat round color="grey-4" icon="bookmark" />
            <q-btn flat round color="grey-4" icon="share" />
          </q-card-actions>
        </q-card>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "PageIndex",
});
</script>
