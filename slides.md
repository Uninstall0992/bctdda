---
# try also 'default' to start simple
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
image: '/image/1.jpg'
# some information about your slides (markdown enabled)
title: Báo cáo tiến độ đồ án
# apply UnoCSS classes to the current slide
layout: intro-image
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
preload: true
---

<div class="absolute top-10" bg="black op-50">
  <span class="font-700">
    Nhóm 1 - 8 con báo Độc Nhất Vô Nhị lên đỉnh Olympius
  </span>
</div>


<div class="absolute bottom-10">
  <h1 bg="black op-50" >Báo cáo tiến độ đồ án</h1>
  <p bg="black op-50" text-align="center"> Lần 1 </p>
</div>
<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: intro
class: px-35
glowSeed: 205
---

# Thành viên & Vai trò

<div flex>
  <div
    v-click="1" flex flex-col items-center transition duration-500 ease-in-out
    :class="$clicks < 1 ? 'translate-y-20 opacity-0' : 'translate-y-0 opacity-100'"
  >
    <img src="/person/1.png" w-50 h-50 rounded-full object-cover mb-5>
    <span font-semibold text-2xl>Nguyễn Khải Toàn</span>
    <div items-center>
      <div>
        <span class="opacity-70">Thành viên</span>
      </div>
      <div text-sm flex items-center justify-center gap-2 mt-4>
        <div i-ri:bookmark-fill /><span underline decoration-dashed font-mono decoration-zinc-300>25127158</span>
      </div>
    </div>
  </div>
  <div flex-1 />
  <div
    v-click="2" flex flex-col items-center transition duration-500 ease-in-out
    :class="$clicks < 2 ? 'translate-y-20 opacity-0' : 'translate-y-0 opacity-100'"
  >
    <img src="/person/2.png" w-50 h-50 rounded-full object-cover mb-5>
    <span font-semibold text-2xl>Nguyễn Quốc Khánh</span>
    <div items-center>
      <div>
        <span class="opacity-70">Thành viên</span>
      </div>
      <div text-sm flex items-center justify-center gap-2 mt-4>
        <div i-ri:bookmark-fill /><span underline decoration-dashed font-mono decoration-zinc-300>25127076</span>
      </div>
    </div>
  </div>
  <div flex-1 />
  <div
    v-click="3" flex flex-col items-center transition duration-500 ease-in-out
    :class="$clicks < 3 ? 'translate-y-20 opacity-0' : 'translate-y-0 opacity-100'"
  >
    <img src="/person/3.png" w-50 h-50 rounded-full object-cover mb-5>
    <span font-semibold text-2xl>Mai Trung Hiếu</span>
    <div flex-col items-center>
      <div>
        <span class="opacity-70">Thành viên</span>
      </div>
      <div text-sm flex items-center justify-center gap-2 mt-4>
        <div i-ri:bookmark-fill /><span underline decoration-dashed font-mono decoration-zinc-300>25127329</span>
      </div>
    </div>
  </div>
</div>

---
layout: intro
class: px-35
glowSeed: 205
---

<div flex>
  <div
    v-click="1" flex flex-col items-center transition duration-500 ease-in-out
    :class="$clicks < 1 ? 'translate-y-20 opacity-0' : 'translate-y-0 opacity-100'"
  >
    <img src="/person/4.png" w-50 h-50 rounded-full object-cover mb-5>
    <span font-semibold text-2xl >Trần Kiến Quốc</span>
    <div items-center>
      <div>
        <span class="opacity-70">Nhóm trưởng</span>
      </div>
      <div text-sm flex items-center justify-center gap-2 mt-4>
        <div i-ri:bookmark-fill /><span underline decoration-dashed font-mono decoration-zinc-300>25127486</span>
      </div>
    </div>
  </div>
  <div flex-1 />
  <div
    v-click="2" flex flex-col items-center transition duration-500 ease-in-out
    :class="$clicks < 2 ? 'translate-y-20 opacity-0' : 'translate-y-0 opacity-100'"
  >
    <img src="/person/5.png" w-50 h-50 rounded-full object-cover mb-5>
    <span font-semibold text-2xl>Hiếu Anh Thư</span>
    <div items-center>
      <div>
        <span class="opacity-70">Thành viên</span>
      </div>
      <div text-sm flex items-center justify-center gap-2 mt-4>
        <div i-ri:bookmark-fill /><span underline decoration-dashed font-mono decoration-zinc-300>25127240</span>
      </div>
    </div>
  </div>
  <div flex-1 />
  <div
    v-click="3" flex flex-col items-center transition duration-500 ease-in-out
    :class="$clicks < 3 ? 'translate-y-20 opacity-0' : 'translate-y-0 opacity-100'"
  >
    <img src="/person/6.png" w-50 h-50 rounded-full object-cover mb-5>
    <span font-semibold text-2xl>Võ Trần Nhật Hạ</span>
    <div flex-col items-center>
      <div>
        <span class="opacity-70">Thành viên</span>
      </div>
      <div text-sm flex items-center justify-center gap-2 mt-4>
        <div i-ri:bookmark-fill /><span underline decoration-dashed font-mono decoration-zinc-300>25127043</span>
      </div>
    </div>
  </div>
</div>

---
layout: intro
class: px-35
glowSeed: 205
---

<div flex>
  <div
    v-click="1" flex flex-col items-center transition duration-500 ease-in-out
    :class="$clicks < 1 ? 'translate-y-20 opacity-0' : 'translate-y-0 opacity-100'"
  >
    <img src="/person/7.png" w-50 h-50 rounded-full object-cover mb-5>
    <span font-semibold text-2xl>Đàm Anh Tuấn</span>
    <div items-center>
      <div>
        <span class="opacity-70">Thành viên</span>
      </div>
      <div text-sm flex items-center justify-center gap-2 mt-4>
        <div i-ri:bookmark-fill /><span underline decoration-dashed font-mono decoration-zinc-300>25127542</span>
      </div>
    </div>
  </div>
</div>



---
class: py-10
glowSeed: 100
---

# Vấn đề
<span>Những vấn đề nhóm mong muốn giải quyết</span>

<div mt-6 grid grid-cols-2 gap-6>
  <div
    v-click
    border="2 solid red-800" bg="red-800/20"
    rounded-lg overflow-hidden
  >
    <div bg="red-800/40" px-4 py-2 flex items-center>
      <div i-carbon:text-align-left text-red-300 text-xl mr-2 />
      <span font-bold>Kịch bản</span>
    </div>
    <div px-4 py-3 flex flex-col gap-2>
      <div flex items-center gap-2 py-1>
        <div i-carbon:spell-check text-amber-300 text-xl />
        <div>
          <div font-bold>Nội dung</div>
          <div text-sm opacity-80>Kịch bản còn thô sơ</div>
        </div>
      </div>
      <div flex items-center gap-2 py-1>
        <div i-carbon:chat text-amber-300 text-xl />
        <div>
          <div font-bold>Thông điệp</div>
          <div text-sm opacity-80>Nhóm chưa làm cô đọng kịch bản thành một câu thông điệp ngắn gọn được</div>
        </div>
      </div>
    </div>
  </div>

  <div
    v-click
    border="2 solid red-800" bg="red-800/20"
    rounded-lg overflow-hidden
  >
    <div bg="red-800/40" px-4 py-2 flex items-center>
      <div i-carbon:product text-red-300 text-xl mr-2 />
      <span font-bold>Sản xuất</span>
    </div>
    <div px-4 py-3 flex flex-col gap-2 h-full>
      <div bg="red-900/30" rounded-lg p-3 flex flex-col gap-2>
        <div font-bold text-sm> Nhóm chưa bàn luận trọn vẹn về những vấn đề sau khi có kịch bản như</div>
        <div flex items-center gap-2>
          <div i-carbon:location text-yellow-400 />
          <span text-sm>Bối cảnh</span>
        </div>
        <div flex items-center gap-2>
          <div i-carbon:person text-yellow-400 />
          <span text-sm>Diễn viên</span>
        </div>
        <div flex items-center gap-2>
          <div i-carbon:hanging-protocol text-yellow-400 />
          <span text-sm>Trang phục</span>
        </div>
                <div flex items-center gap-2>
          <div i-carbon:cost text-yellow-400 />
          <span text-sm>Chi phí</span>
        </div>
        <div flex items-center gap-2>
          <div i-carbon:camera text-yellow-400 />
          <span text-sm>Quay dựng</span>
        </div>
        <div flex items-center gap-2>
          <div i-carbon:video text-yellow-400 />
          <span text-sm>Hậu kỳ</span>
        </div>
      </div>
      </div>
    </div>
</div>

---
class: py-10
glow: right
---

# Các cuộc họp

<div mt-6 />

<div flex>
  <div flex-1 pr-0>
    <div
      v-motion
      :initial="{ opacity: 0, y: 50 }"
      :enter="{ opacity: 1, y: 0, transition: { delay: 200 } }"
      border="2 solid purple-800" bg="purple-800/20"
      rounded-lg p-4
    >
      <div flex items-center>
        <div i-carbon:location text-3xl mr-2 />
        <span font-bold>Địa điểm</span>
      <div>
        <div text-sm font-medium>Ngày 1/11: Sảnh I</div>
        <div text-xs opacity-70>Trường Đại học Khoa học Tự nhiên, Đại học Quốc gia Thành phố Hồ Chí Minh</div>
        <div text-sm font-medium>Ngày 13/11: Namoo Coffee</div>
        <div text-xs opacity-70>103 Cao Thắng, phường Bàn Cờ, Thành phố Hồ Chí Minh</div>
      </div>
      </div>
    </div>
    <div
      v-motion
      :initial="{ opacity: 0, y: 50 }"
      :enter="{ opacity: 1, y: 0, transition: { delay: 400 } }"
      mt-4 border="2 solid red-800" bg="red-800/20"
      rounded-lg p-4
    >
      <div flex items-center>
        <div i-carbon:task text-red-300 text-xl mr-2 />
        <span font-bold>Mục tiêu</span>
      </div>
    <div px-5 py-4 flex flex-col gap-2>
      <div
        v-for="(item) in [
          'Chỉnh sửa kịch bản, phân chia vai diễn phù hợp.',
          'Bàn về bối cảnh, timeline quay video đồ án kỹ năng mềm.',
        ]"
        :key="item"
        v-click="1"
        flex items-center gap-2
        transition duration-300 ease-in-out
      >
        <div i-carbon:checkmark text-red-400 />
        <span>{{item}}</span>
      </div>
    </div>
    </div>
  </div>

  <div flex-1 pl-4>
    <div
      v-motion
      :initial="{ opacity: 0, y: 50 }"
      :enter="{ opacity: 1, y: 0, transition: { delay: 600 } }"
      border="2 solid blue-800" bg="blue-800/20"
      rounded-lg p-4 h-full
    >
      <div flex items-center>
        <div i-carbon:list-checked mr-2 />
        <span font-bold>Nội dung</span>
      </div>
      <div mt-4 flex flex-col gap-2>
        <div
          v-click="2"
        >
    <div px-4 py-3 flex flex-col gap-2 h-full>
      <div bg="blue-900/30" rounded-lg p-3 flex flex-col gap-2>
        <div font-bold text-sm>Ngày 1/11</div>
        <div flex items-center gap-2>
          <div i-carbon:checkmark-outline text-blue-400 />
          <span text-sm>Cải tổ nhóm - bầu lại nhóm trưởng, nhóm phó: Trần Kiến Quốc & Mai Trung Hiếu</span>
        </div>
        <div flex items-center gap-2>
          <div i-carbon:checkmark-outline text-blue-400 />
          <span text-sm>Bàn về khung nội dung video gồm: Hình thức & Nội dung kịch bản sơ bộ</span>
        </div>
      </div>
    </div>
    <div px-4 py-3 flex flex-col gap-2 h-full>
      <div bg="blue-900/30" rounded-lg p-3 flex flex-col gap-2>
        <div font-bold text-sm>Ngày 13/11</div>
        <div flex items-center gap-2>
          <div i-carbon:checkmark-outline text-blue-400 />
          <span text-sm>Thảo luận để đưa ra được giải pháp cho những vấn đề trong buổi họp trước</span>
        </div>
        <div flex items-center gap-2>
          <div i-carbon:checkmark-outline text-blue-400 />
          <span text-sm>Đưa ra ý tưởng để thực hiện bước chuẩn bị tiếp theo của đồ án</span>
        </div>
      </div>
    </div>
        </div>
      </div>
    </div>
  </div>
</div>

---
layout: 3-images
imageLeft: '/image/1.jpg'
imageTopRight: '/image/2.jpg'
imageBottomRight: '/image/3.jpg'
---

---
class: py-10
glowSeed: 100
---

# Kết quả

<span>Những nội dung đã được thống nhất trong những buổi thảo luận</span>

<div mt-6 />

<div grid grid-cols-3 gap-3 h-75>

<v-clicks>

<div border="2 solid white/5" rounded-lg overflow-hidden bg="white/5" backdrop-blur-sm h-full>
  <div flex items-center bg="white/10" backdrop-blur px-3 py-2 rounded-md>
    <div i-carbon:warning-alt text-amber-300 text-sm mr-2 />
    <div font-semibold>
      Kịch bản
    </div>
  </div>
  <div px-4 py-3>
    <div flex flex-col gap-3>
      <div>
        <div text-sm font-medium>Chủ đề</div>
        <div text-xs opacity-70>Gender Equality (Bình đẳng giới) & Domestic Violence (Bạo lực gia đình)</div>
      </div>
      <div>
        <div text-sm font-medium>Thời lượng tổng</div>
        <div text-xs opacity-70>~8 phút (Tùy chỉnh dựa vào tình hình thực tế)</div>
      </div>
      <div>
        <div text-sm font-medium>Phân đoạn chính & Số lượng cảnh quay</div>
        <div text-xs opacity-70>4 (sequences), 8 (scenes)</div>
      </div>
      <div>
        <div text-sm font-medium>Tổng diễn viên</div>
        <div text-xs opacity-70>2 vai chính (1 nam/nữ) và 6 vai phụ</div>
      </div>
    </div>
  </div>
</div>

<div border="2 solid white/5" rounded-lg overflow-hidden bg="white/5" backdrop-blur-sm h-full>
  <div flex items-center bg="white/10" backdrop-blur px-3 py-2 rounded-md>
    <div i-carbon:download text-blue-300 text-sm mr-2 />
    <div font-semibold>
      Bối cảnh
    </div>
  </div>
  <div px-4 py-3>
    <div flex flex-col gap-3>
      <div>
        <div text-sm font-medium>Sân trường</div>
        <div text-xs opacity-70>Đại học Khoa Học Tự Nhiên (cơ sở 1)
        </div>
        <div text-sm font-medium>Studio</div>
        <div text-xs opacity-70>854 Tạ Quang Bửu,  phường Bình Đông, Thành phố Hồ Chí Minh
        </div>
        <div text-sm font-medium>Cafe</div>
        <div text-xs opacity-70>Gần studio
        </div>
      </div>
    </div>
  </div>
</div>

<div border="2 solid white/5" rounded-lg overflow-hidden bg="white/5" backdrop-blur-sm h-full>
  <div flex items-center bg="white/10" backdrop-blur px-3 py-2 rounded-md>
    <div i-carbon:data-check text-green-300 text-sm mr-2 />
    <div font-semibold>
      Kỹ thuật 
    </div>
  </div>
  <div px-4 py-3>
    <div flex flex-col gap-3>
      <div>
        <div text-sm font-medium>Âm thanh</div>
        <div text-xs opacity-70>Davinci Resolve</div>
      </div>
      <div>
        <div text-sm font-medium>Video</div>
        <div text-xs opacity-70>Capcut</div>
      </div>
    </div>
  </div>
</div>

</v-clicks>

</div>

<div v-click mt-6 flex justify-center>
  <div
    border="2 solid white/5" bg="white/5" backdrop-blur-sm
    rounded-lg px-6 py-3 flex items-center gap-3
  >
    <div i-carbon:idea text-yellow-300 text-2xl />
    <span text-lg>Chi phí: Dự kiến 1,5 triệu tiền thuê studio</span>
  </div>
</div>

---

# Timeline

```mermaid 
timeline
    section Quay video 
    15/11/2025  : Lorem
    section Chỉnh sửa 
    29/11/2025   : Lorem
    section Rà Soát 
    6/12/2025 : Lorem
    section Hậu kỳ 
    13/12/2025 : Lorem
    section Hoàn thiện đồ án 
    20/12/2025 : Lorem
```

---
class: py-10
glow: left
---

# Kế hoạch

<span>Các kế hoạch của nhóm</span>

<div mt-4 />

<div flex justify-center>
  <div
    v-motion
    :initial="{ opacity: 0, y: 40 }"
    :enter="{ opacity: 1, y: 0, transition: { duration: 600 } }"
    grid grid-cols-3 gap-4 w-full text-sm
  >
    <div
      v-click="1"
      border="2 solid yellow-800" bg="yellow-800/20"
      rounded-lg overflow-hidden transition-all duration-500
      :class="$clicks === 5 ? 'opacity-40' : ''"
    >
      <div bg="yellow-800/40" px-4 py-3 flex items-center>
        <div i-carbon:money text-3xl mr-3 />
        <span font-bold>Tài chính</span>
      </div>
      <div px-4 py-3 flex flex-col gap-2>
        <div flex items-center gap-2>
          <div />
          <span>Nhà hảo tâm: Trần Kiến Quốc & Võ Trần Nhật Hạ</span>
        </div>
        <div flex items-center gap-2>
          <div />
          <span>Tận dụng những bối cảnh và dụng cụ quay có sẵn, hai nhà hảo tâm sẽ tài trợ phần lớn tài chính vào nhóm để hỗ trợ những thành viên còn lại.</span>
        </div>
      </div>
    </div>
    <div
      v-click="2"
      border="2 solid cyan-800" bg="cyan-800/20"
      rounded-lg overflow-hidden transition-all duration-500
      :class="$clicks === 5 ? 'opacity-40' : ''"
    >
      <div bg="cyan-800/40" px-4 py-3 flex items-center>
        <div i-carbon:delivery text-3xl mr-3 />
        <span font-bold>Thực hiện</span>
      </div>
      <div px-4 py-3 flex flex-col gap-2>
        <div flex items-center gap-2>
          <div text-green-400 />
          <span>Trước tuần diễn, thành viên đảm nhiệm chuẩn bị đạo cụ quay. Bàn bạc và chốt về trang phục.</span>
        </div>
        <div flex items-center gap-2>
          <div text-red-400 />
          <span>Trước 3 ngày diễn, nhóm trưởng thông báo mọi người học thuộc kịch bản.</span>
        </div>
      </div>
    </div>
    <div
      v-click="3"
      border="2 solid blue-800" bg="blue-800/20"
      rounded-lg overflow-hidden transition-all duration-500
      :class="$clicks === 5 ? 'opacity-40' : ''"
    >
      <div bg="blue-800/40" px-4 py-3 flex items-center>
        <div i-carbon:phone text-3xl mr-3 />
        <span font-bold>Liên lạc</span>
      </div>
      <div px-4 py-3 flex flex-col gap-2>
        <div flex items-center gap-2>
          <div text-red-400 />
          <span>Thông báo trước ít nhất 1 tuần về địa điểm quay thông qua Messenger. Các thành viên sẽ gửi emoji hoặc phản hồi tin nhắn để được đánh dấu là đã nhận được tin nhắn.</span>
        </div>
      </div>
    </div>
  </div>
</div>

<div
  v-click="4"
  mt-4 transition-all duration-500
  :class="$clicks < 4 ? 'opacity-0 scale-95' : 'opacity-100 scale-100'"
>
  <div flex items-center justify-center>
    <div relative>
      <div
        border="2 solid green-800" bg="green-800/20"
        rounded-lg p-4 w-full>
        <div text-center font-bold text-xl mb-3>Lấy ý kiến</div>
          <div flex items-center gap-2>
            <div text-green-400 />
            <span >Nhóm tích cực nghe ý kiến từ thầy cô và các bạn sau buổi xem video, rút ra những bài học quý giá cho những dự án của các môn sau này, mọi thành viên trong nhóm sẽ hướng đến những kinh nghiệm quý báu cho tương lai sau này.</span>
          </div>
      </div>
    </div>
  </div>
</div>

---
layout: statement
---

# Cảm ơn thầy cô và các bạn

<div class="absolute bottom-10">
  <p text-align="center"> Biễu mẫu: Slidev - Anthony Fu & Taming Dependency Chaos for LLM in K8S - Kebe Liu</p>
</div> 