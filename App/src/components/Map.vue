<template>
<div>
       <h1 class="Main_font">What are you looking for?</h1>
           <div>
                <v-container>
                    <v-layout row wrap style="justify-content: center;">
                        <v-flex class="customflex">
                            <img class="Map_images" src="@/assets/userIMG.png" />
                            <h2 class="Image_font">User</h2>
                        </v-flex>
                        <v-flex class="customflex">
                            <img class="Map_images" src="@/assets/placeIMG.png" />
                            <h2 class="Image_font">Place</h2>
                        </v-flex>
                        <v-flex class="customflex">
                            <img class="Map_images" src="@/assets/objectIMG.png"  />
                            <h2 class="Image_font">Object</h2>
                        </v-flex>
                    </v-layout>
                </v-container>
            </div>
        
</div>
</template>


<style scoped>
.Main_font {
    color: #646464;
    font-family: Agency FB;
    font-style: normal;
    font-size: 44px;
    text-align: center;
    font-weight: normal;
    letter-spacing: 1px;
    word-spacing: 5px;
}

.Map_images {

    margin-left: 12px;
    margin-right: 12px;
    margin-top: 5px;
    margin-bottom: 0px;
    height: 242px;
    width: 250px;
}

.Image_font {
    color: #cdcdcd;
    font-family: Agency FB;
    font-style: normal;
    font-size: 30px;
    text-align: center;
    font-weight: normal;
    letter-spacing: 1px;
}

.customflex
{
    flex: 0 1 auto;
}

</style>




