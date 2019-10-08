<template>
<v-container>
    <v-row
    >
      <v-col cols="12">
<v-card
class="listItems"
    tile
  >
    <div>
        <ul class="list-group" text-center>
            <li class="list-group-item" v-for="index in 5">
                Server #{{ index }}
            </li>
        </ul>
    </div>
    </v-card>
    </v-col>
     </v-row>
    </v-container>
   
</template>

<script>

</script>

<style scoped>
ul.list-group {
    list-style-type: none;
}
.listItems {
    display: flex;
    justify-content: center;
}

</style>
