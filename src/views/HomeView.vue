<script setup>
import { toast } from 'vue3-toastify';
import 'vue3-toastify/dist/index.css';

toast.info("ยินดีต้อนรับแผนกเทคโนโลยีสารสนเทศ", {
  autoClose: 1500,
  position:toast.POSITION.TOP_CENTER
})

const notify = () => {
  toast.success("ยินดีต้อนรับแผนกเทคโนโลยีสารสนเทศ", {
    autoClose: 1500,
    position: toast.POSITION.TOP_CENTER
  })
  return notify
}

</script>

<template>
  <div class="container my-5">
    <div class="card shadow" style="width: 20rem;">
      <div class="card-header p-0">
        <img src="https://image.makewebcdn.com/makeweb/m_1920x0/oDgJmY2kJ/DefaultData/10_%E0%B8%AA%E0%B8%96%E0%B8%B2%E0%B8%99%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%97%E0%B9%88%E0%B8%AD%E0%B8%87%E0%B9%80%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%A7%E0%B9%83%E0%B8%99%E0%B9%84%E0%B8%97%E0%B8%A2%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%95%E0%B8%B4%E0%B8%94%E0%B8%AD%E0%B8%B1%E0%B8%99%E0%B8%94%E0%B8%B1%E0%B8%9A%E0%B9%82%E0%B8%A5%E0%B8%81_copy.jpg" class="card-img-top"
          alt="img">
      </div>
      <div class="card-body">
        <h5 class="card-title">สถานที่ท่องเที่ยว</h5>
        <p class="card-text"> ใน ประเทศไทย บ้านเรามีที่เที่ยวเยอะแยะแบบที่ไปกันได้ทั้งปีทุกวี่ทุกวันก็ยังไม่มีหมดค่ะ นี่ยังไม่นับรวมแหล่งท่องเที่ยวใหม่ๆ ที่ผุดกันขึ้นมาเรื่อยๆ เรียกได้ว่าเมืองไทยของเรานั้น แทบจะเป็นสวรรค์ของนักท่องเที่ยวกันเลย</p>
        <a href="#" class="btn btn-primary" @click="notify" style="background: #eb7ce5">Read...</a>
      </div>
    </div>
  </div>
</template>
