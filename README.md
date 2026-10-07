# h-c-lieu-h-c-tap
description:"Lịch sử Việt Nam và thế giới"
},

{
    name:"Địa lí",
    icon:"🌍",
    description:"Tự nhiên • Dân cư • Kinh tế"
},

{
    name:"Sinh học",
    icon:"🧬",
    description:"Sự sống • Cơ thể • Di truyền"
},

{
    name:"Vật lí",
    icon:"⚡",
    description:"Cơ học • Nhiệt • Điện • Quang"
},

{
    name:"Hóa học",
    icon:"🧪",
    description:"Chất • Phản ứng • Hóa hữu cơ"
},

{
    name:"Kinh tế & Pháp luật",
    icon:"⚖️",
    description:"Kinh tế • Pháp luật • Công dân"
},

{
    name:"Tin học",
    icon:"💻",
    description:"Máy tính • Thuật toán • Lập trình"
},

{
    name:"Công nghệ",
    icon:"🔧",
    description:"Kĩ thuật • Công nghệ • Đời sống"
},

{
    name:"Tổng hợp",
    icon:"🎯",
    description:"Thử thách kiến thức tổng hợp"
}

];


/* =====================================================
   BIẾN HỆ THỐNG
===================================================== */

let currentSubject = null;

let currentGrade = null;

let currentMode = null;

let currentChapter = null;

let currentQuestionIndex = 0;

let score = 0;

let selectedQuestions = [];


/* =====================================================
   DỮ LIỆU BÀI HỌC MẪU
===================================================== */

const l
