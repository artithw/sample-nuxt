<template>
  <v-card>
    <v-card-title class="headline font-weight-regular teal white--text">
      เข้าเน็ตไม่ได้ {ดำเนินการแล้ว}
    </v-card-title>
    <v-form>
      <v-container>
        <v-row>
          <v-col cols="12" md="6">
            <v-textarea outlined label="รายละเอียด"></v-textarea>
            <v-text-field
              filled
              color="blue-grey lighten-2"
              label="สถานที่"
            ></v-text-field>
            <v-text-field
              filled
              color="blue-grey lighten-2"
              label="วันที่"
            ></v-text-field>
          </v-col>
          <v-col cols="12" md="6">
            <v-col cols="5">
              <div class="title mb-1">รูปภาพ</div>
              <div class="subheading">Matching</div>
              <v-img
                src="https://picsum.photos/510/300?random"
                aspect-ratio="1.7"
              ></v-img>
            </v-col>
          </v-col>
          <v-col cols="12"> </v-col>
        </v-row>
      </v-container>
    </v-form>
    <v-card-title class="headline font-weight-regular teal white--text">
      เจ้าหน้าที่
    </v-card-title>
    <v-form>
      <v-container>
        <v-row>
          <v-col cols="12" md="6">
            <v-textarea outlined label="รายละเอียด"></v-textarea>
            <v-text-field
              filled
              color="blue-grey lighten-2"
              label="สถานะ"
            ></v-text-field>
            <v-text-field
              filled
              color="blue-grey lighten-2"
              label="วันที่"
            ></v-text-field>
          </v-col>
          <v-col cols="12" md="6">
            <v-col cols="5">
              <div class="title mb-1">รูปภาพ</div>
              <div class="subheading">Matching</div>
              <v-img
                src="https://picsum.photos/510/300?random"
                aspect-ratio="1.7"
              ></v-img>
            </v-col>
          </v-col>
          <v-col cols="12"> </v-col>
        </v-row>
      </v-container>
    </v-form>
  </v-card>
</template>
