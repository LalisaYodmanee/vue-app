<script setup >
import { ref } from "vue"
const stuID =ref("");
const stuName =ref("");
const checkbox =ref("");

</script>
<template>
    <h1></h1><h1>คำร้องขอลาออก</h1>
    เขียนที่ มหาวิทยาลัยแม่โจ้
    <h1></h1>วันที่....เดือน..............พ.ศ.25........
<form >
  <h1></h1><p>เรื่อง ขอลาออก</p> 
  <p>เรียน อธิการบดี ผ่านคณบดี คณะ...................................</p>
  ข้าพเจ้า <input type="checkbox" name="" id="">นาย
  <input type="checkbox" name="" id="">นาง
  <input type="checkbox" name="" id="">นางสาว ชื่อ-นามสกุล<input type="text" v-model="stuName" name="stuName" id="stuName" maxlength="100">

  <h1></h1>รหัสนักศึกษา<input type="text" v-model="stuID" name="stuID" id="stuID">
  เบอร์โทรศัพท์<input type="data" name="" id="">โปรดระบุ
<h1></h1>คณะ
<select name="" id="">
<option> กรุณาเลือก</option>
<option> คณะวิทยาศาสตร์</option>
<option> บริหาร</option>
<option> ท่องเที่ยว</option>
<option> ศิลปศาสตร์</option>
<option> พลังงานทดแทน</option>
<option> พยาบาล</option>
<option> เศรษฐศาตร์</option>
<option> สัตวศาสตร์</option>
</select>
สาขา
<select name="" id="">
<option> กรุณาเลือก</option>
<option>วิทยาการคอมพิวเตอร์</option>
<option>เคมี</option>
<option>คณิตศาสตร์</option>
</select>
หลักสูตร
<select name="" id="">
<option> </option>
<option>4 ปี</option>
<option>4-5 ปี</option>
<option>เทียบเข้าเรียน 2 ปี </option>
</select>
<h1></h1>
<input type="checkbox" name="" id="">
ภาคปกติ 
<input type="checkbox" name="" id="">
ภาคสมทบ
<h1></h1>
<h1></h1>
มีความประสงค์จะขอลาออก เนื่องจาก.......................................................................................................
<h1></h1>
พร้อมนี้ได้แนบยินยอมจากผู้ปกครอง
<h1></h1>จึงเรียนมาเพื่อทราบ
<br>
<h1></h1>ขอแสดงความนับถือ
<h1></h1>(....................................)
<h1></h1>นักศึกษา 
<h1></h1>
<span></span>
<p style="">{{ message }}</p>
<br>
ความเห็นของอาจารที่ปรึกษา<h1></h1>
<input type="checkbox" name="" id="">ทราบ........................                 
<h1></h1>
<textarea v-model="message" placeholder="add multiple lines"></textarea>
<textarea v-model="message" placeholder="add multiple lines"></textarea>
<br>
ความเห็นประธานอาจารย์ประจำหลักสูตร<h1></h1>
<input type="checkbox" name="" id="">ทราบ.........................
<h1></h1>
<textarea v-model="message" placeholder="add multiple lines"></textarea>
<textarea v-model="message" placeholder="add multiple lines"></textarea><p style="">{{ message }}</p>
ความเห็นคณะบดี<h1></h1>
<input type="checkbox" name="" id="">ทราบ.........................
<br>
ความเห็นผู้อำนวยการสำนักบริหารและพัฒนาวิชาการ
<h1></h1>
<input type="checkbox" name="" id="">ทราบ.........................
<br>
<textarea v-model="message" placeholder="add multiple lines"></textarea>
<textarea v-model="message" placeholder="add multiple lines"></textarea>
<h1></h1> 
ความเห็นอธิการบดี<h1></h1>
<input type="checkbox" name="" id="">ทราบ.........................
<br>
<textarea v-model="message" placeholder="add multiple lines"></textarea>
<textarea v-model="message" placeholder="add multiple lines"></textarea>
<h1></h1>
<input type="submit" value="ยืนยัน">
</form>
</template>

<script setup >

</script>

<style scoped>
 
</style>