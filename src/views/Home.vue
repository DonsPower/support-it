<template>
   <v-container>
    <v-toolbar
      dense
      floating
    >
      <v-text-field
        hide-details
        prepend-icon="mdi-magnify"
        single-line
        
      ></v-text-field>
       
      <v-btn icon>
        <v-icon>mdi-crosshairs-gps</v-icon>
      </v-btn>
    </v-toolbar>
    
    <v-row justify="center" >
      <v-col cols="12">
        <v-img
          :src="require('../img/logo.jpg')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col class="mb-4 text-center">
        
        <h1 class="display-2 font-weight-bold mb-3">
          Control de Soporte Central
        </h1>

        
      </v-col>

    </v-row>

<v-bottom-navigation
    :value="value"
    color="primary"
    horizontal
  >
    <v-btn 
      to="/About"
    >
      <span>Candados</span>

      <v-icon>mdi-application-cog</v-icon>
    </v-btn>

    <v-btn>
      <span>Liquidaciones</span>

      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn>
      <span>Nearby</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
     <v-btn>
      <span>Nearby</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
     <v-btn>
      <span>Nearby</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
     <v-btn>
      <span>Nearby</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
     <v-btn>
      <span>Nearby</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
     <v-btn>
      <span>Nearby</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
     <v-btn>
      <span>Nearby</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
  </v-bottom-navigation>
  </v-container>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  
}
</script>
