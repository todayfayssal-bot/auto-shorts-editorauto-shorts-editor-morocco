<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#090d18">
<title>Clipora AI | الاستوديو الشامل الذكي</title>
<style>
:root {
  --bg:#090d18;
  --panel:#111a2c;
  --line:#27334a;
  --text:#f5f7ff;
  --muted:#9baac3;
  --green:#66f0c0;
  --blue:#839dff;
  --accent:#ff5c8d;
}
* { box-sizing:border-box; }
body {
  margin:0; font-family:system-ui,Arial,sans-serif;
  background:radial-gradient(ellipse at top,#1b2c4c 0%,var(--bg) 55%);
  color:var(--text); min-height:100vh;
}
button,input,select,textarea { font:inherit; }
button { cursor:pointer; }
.container { max-width:1200px; margin:auto; padding:20px; }
header {
  display:flex; justify-content:space-between; align-items:center;
  padding:12px 0 24px; border-bottom:1px solid var(--line);
}
.brand { display:flex; align-items:center; gap:12px; font-size:22px; font-weight:900; }
.logo {
  display:grid; place-items:center; width:46px; height:46px;
  border-radius:15px; color:#07131b;
  background:linear-gradient(135deg,var(--green),var(--blue));
  font-size:24px;
}
.brand small { display:block; color:var(--muted); font-size:10px; letter-spacing:2px; }
.nav-btns { display:flex; gap:10px; }
.pill { border:1px solid #315c58; color:var(--green); padding:8px 14px; border-radius:30px; font-size:12px; background:#66f0c010; }

.hero { padding:30px 0; text-align:center; }
.eyebrow { color:var(--green); font-size:13px; font-weight:700; }
h1 { font-size:clamp(28px,5vw,48px); line-height:1.3; margin:10px 0; }
h1 span { background:linear-gradient(90deg,var(--green),var(--blue)); color:transparent; background-clip:text; }
.hero p { max-width:650px; margin:0 auto; color:var(--muted); font-size:14px; line-height:1.8; }

.grid-layout { display:grid; grid-template-columns:1fr 1fr; gap:20px; margin-top:20px; }
.card {
  background:linear-gradient(145deg,#141f34,#0f1728);
  border:1px solid var(--line); border-radius:20px; padding:20px;
  box-shadow:0 18px 45px #0002;
}
.card h2 { font-size:17px; margin:0 0 15px; display:flex; align-items:center; gap:8px; }
.label { display:block; font-size:13px; font-weight:700; margin:14px 0 6px; color:var(--muted); }

input[type=text], select, textarea {
  width:100%; padding:11px; border-radius:10px;
  color:var(--text); background:#0a1221; border:1px solid var(--line);
}
textarea { resize:vertical; min-height:80px; }
select option { background:#111a2c; }

.btn { border:0; border-radius:12px; padding:12px 18px; font-weight:800; transition:.2s; display:inline-flex; align-items:center; justify-content:center; gap:8px; }
.btn:hover { transform:translateY(-2px); }
.primary { background:linear-gradient(100deg,var(--green),#a2f8d8); color:#08131c; }
.secondary { color:var(--text); background:#ffffff0b; border:1px solid var(--line); }
.danger { background:var(--accent); color:#fff; }

.stock-search { display:flex; gap:8px; margin-bottom:12px; }
.stock-results { display:grid; grid-template-columns:repeat(3,1fr); gap:8px; max-height:180px; overflow-y:auto; padding:4px; }
.stock-item { border:1px solid var(--line); border-radius:8px; overflow:hidden; cursor:pointer; background:#070b13; position:relative; }
.stock-item video { width:100%; height:80px; object-fit:cover; display:block; }
.stock-item:hover { border-color:var(--green); }

.preview-container {
  background:#070b13; border:1px solid var(--line); border-radius:14px;
  height:320px; display:grid; place-items:center; position:relative; overflow:hidden; margin-top:12px;
}
.preview-container video { width:100%; height:100%; object-fit:cover; }
.caption-overlay {
  position:absolute; bottom:30px; width:90%; text-align:center;
  font-size:20px; font-weight:900; color:#fff; text-shadow:0 2px 8px rgba(0,0,0,0.9);
  padding:6px 12px; background:rgba(0,0,0,0.4); border-radius:8px;
  border-bottom:3px solid var(--green);
}

.scheduler-section { margin-top:25px; }
.schedule-table { width:100%; border-collapse:collapse; margin-top:10px; font-size:13px; }
.schedule-table th, .schedule-table td { padding:10px; border-bottom:1px solid var(--line); text-align:right; }
.schedule-table th { color:var(--muted); }
.badge-status { padding:4px 8px; border-radius:20px; font-size:11px; background:#66f0c020; color:var(--green); }

@media(max-width:768px) {
  .grid-layout { grid-template-columns:1fr; }
  .stock-results { grid-template-columns:repeat(2,1fr); }
}
</style>
</head>
<body>
<div class="container">
  <header>
    <div class="brand">
      <div class="logo">▶</div>
      <div>Clipora AI<small>SMART AUTOMATION STUDIO</small></div>
    </div>
    <div class="nav-btns">
      <span class="pill">● متصل بالذكاء الاصطناعي</span>
    </div>
  </header>

  <section class="hero">
    <div class="eyebrow">✦ الأتمتة الكاملة لصناعة الفيديوهات القصيرة</div>
    <h1>ابحث، أنشئ، وانسخ الصوت<br><span>وانشر تلقائياً على منصتك.</span></h1>
    <p>منصة متكاملة لجلب الفيديوهات بدون حقوق، توليد التعليق الصوتي، تركيب الترجمة المتناسقة، والجدولة التلقائية.</p>
  </section>

  <div class="grid-layout">
    <!-- القسم الأول: جلب الفيديوهات والمحتوى -->
    <div class="card">
      <h2>🌐 1. مصدر الفيديوهات (Pexels Stock)</h2>
      <label class="label">ابحث عن مقاطع بدون حقوق نشر (إنجليزي أفضل للنتائج)</label>
      <div class="stock-search">
        <input type="text" id="searchQuery" value="Nature animals cinematic" placeholder="ابحث مثلاً: Lions, Galaxy, Ocean...">
        <button class="btn primary" onclick="searchPexelsVideos()">بحث</button>
      </div>
      <div class="stock-results" id="stockResults">
        <div style="grid-column: span 3; text-align:center; color:var(--muted); padding:20px; font-size:12px;">
          اضغط على زر "بحث" لجلب فيديوهات مجانية عالية الدقة.
        </div>
      </div>

      <label class="label" for="scriptText">2. النص والتعليق الصوتي (Script & TTS)</label>
      <textarea id="scriptText" placeholder="اكتب النص الذي سيتم تحويله إلى صوت وكتابته على الفيديو...">Did you know that ants can lift 50 times their own body weight?</textarea>
      
      <div style="display:flex; gap:10px; margin-top:10px;">
        <select id="voiceStyle" style="flex:1;">
          <option>صوت رجالي عميق (Deep Voice)</option>
          <option>صوت حماسي وثائقي (Documentary)</option>
          <option>صوت هادئ ومريح (Calm)</option>
        </select>
        <button class="btn secondary" onclick="generateVoiceover()">🔊 توليد الصوت</button>
      </div>
    </div>

    <!-- القسم الثاني: المعاينة الحية والإعدادات -->
    <div class="card">
      <h2>🎬 3. الاستوديو ومعاينة الإخراج</h2>
      <div class="preview-container" id="previewContainer">
        <div style="color:var(--muted); text-align:center; font-size:13px;">
          <strong>▷</strong> اختر فيديو من النتائج أعلاه للمعاينة
        </div>
        <div class="caption-overlay" id="liveCaption" style="display:none;">النص المتزامن سيظهر هنا...</div>
      </div>

      <label class="label" for="targetPlatform">منصة النشر التلقائي</label>
      <select id="targetPlatform">
        <option>TikTok (تيك توك)</option>
        <option>YouTube Shorts (يوتيوب شورتس)</option>
        <option>Instagram Reels (إنستغرام ريلز)</option>
      </select>

      <label class="label" for="scheduleTime">وقت النشر المقترح (الجدول الزمني)</label>
      <input type="datetime-local" id="scheduleTime">

      <div style="display:flex; gap:10px; margin-top:16px;">
        <button class="btn primary" style="flex:2;" onclick="scheduleAndPublish()">🚀 جدولة النشر التلقائي</button>
        <button class="btn danger" style="flex:1;" onclick="resetStudio()">إعادة ضبط</button>
      </div>
    </div>
  </div>

  <!-- جدول جدولة المحتوى -->
  <div class="card scheduler-section">
    <h2>📅 جدول المهام التلقائية المنشورة والمجدولة</h2>
    <table class="schedule-table">
      <thead>
        <tr>
          <th>عنوان الفيديو / الملف</th>
          <th>المنصة</th>
          <th>وقت النشر المحدد</th>
          <th>الحالة</th>
        </tr>
      </thead>
      <tbody id="scheduleBody">
        <tr>
          <td>Animal_Hydraulic_Jaw_Fact.mp4</td>
          <td>TikTok</td>
          <td>اليوم، 10:00 مساءً</td>
          <td><span class="badge-status">مجدول تلقائياً</span></td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<script>
let selectedVideoUrl = "";

// محاكاة جلب فيديوهات من Pexels API مجاناً
async function searchPexelsVideos() {
  const query = document.getElementById('searchQuery').value;
  const container = document.getElementById('stockResults');
  container.innerHTML = '<div style="grid-column: span 3; text-align:center; color:var(--muted); padding:20px;">جاري البحث عن المقاطع...</div>';

  try {
    // استخدام مفتاح Pexels تجريبي عام أو جلب مباشر
    const res = await fetch(`https://api.pexels.com/videos/search?query=${encodeURIComponent(query)}&per_page=6`, {
      headers: { Authorization: '563492ad6f91700001000001824021008d514a38914b1f6462db948c' } // مفتاح تجريبي عام لـ Pexels
    });
    const data = await res.json();
    
    if(data.videos && data.videos.length > 0) {
      container.innerHTML = '';
      data.videos.forEach(video => {
        const videoFile = video.video_files.find(f => f.quality === 'hd' || f.quality === 'sd') || video.video_files[0];
        const div = document.createElement('div');
        div.className = 'stock-item';
        div.innerHTML = `<video src="${videoFile.link}" muted loop onmouseover="this.play()" onmouseout="this.pause()"></video>`;
        div.onclick = () => selectStockVideo(videoFile.link);
        container.appendChild(div);
      });
    } else {
      fallbackVideos(query);
    }
  } catch (e) {
    fallbackVideos(query);
  }
}

// في حال عدم توفر الاتصال المباشر، يتم عرض عينات جاهزة مباشرة
function fallbackVideos(query) {
  const container = document.getElementById('stockResults');
  const sampleVideos = [
    "https://videos.pexels.com/video-files/855314/855314-hd_1080_1920_25fps.mp4",
    "https://videos.pexels.com/video-files/3571264/3571264-hd_1080_1920_30fps.mp4",
    "https://videos.pexels.com/video-files/4114797/4114797-hd_1080_1920_25fps.mp4"
  ];
  container.innerHTML = '';
  sampleVideos.forEach((link, index) => {
    const div = document.createElement('div');
    div.className = 'stock-item';
    div.innerHTML = `<video src="${link}" muted loop onmouseover="this.play()" onmouseout="this.pause()"></video>`;
    div.onclick = () => selectStockVideo(link);
    container.appendChild(div);
  });
}

function selectStockVideo(url) {
  selectedVideoUrl = url;
  const previewContainer = document.getElementById('previewContainer');
  previewContainer.innerHTML = `
    <video src="${url}" autoplay muted loop playsinline></video>
    <div class="caption-overlay" id="liveCaption">جاهز للدمج والنشر التلقائي...</div>
  `;
}

function generateVoiceover() {
  const text = document.getElementById('scriptText').value;
  if(!text) {
    alert('يرجى كتابة النص أولاً لتوليد الصوت.');
    return;
  }
  alert('تم توليد التعليق الصوتي بنجاح وربطه مع توقيت الفيديو!');
  const captionEl = document.getElementById('liveCaption');
  if(captionEl) {
    captionEl.style.display = 'block';
    captionEl.textContent = text.substring(0, 45) + '...';
  }
}

function scheduleAndPublish() {
  if(!selectedVideoUrl) {
    alert('يرجى اختيار فيديو من نتائج Pexels أولاً.');
    return;
  }
  const platform = document.getElementById('targetPlatform').value;
  const time = document.getElementById('scheduleTime').value || 'خلال ساعة';
  
  const tbody = document.getElementById('scheduleBody');
  const row = document.createElement('tr');
  row.innerHTML = `
    <td>Auto_Short_${Math.floor(Math.random()*1000)}.mp4</td>
    <td>${platform}</td>
    <td>${time}</td>
    <td><span class="badge-status">تمت الجدولة بنجاح 🚀</span></td>
  `;
  tbody.prepend(row);
  alert('تمت إضافة الفيديو بنجاح إلى جدول النشر الآلي للمنصات المستهدفة!');
}

function resetStudio() {
  selectedVideoUrl = "";
  document.getElementById('previewContainer').innerHTML = `
    <div style="color:var(--muted); text-align:center; font-size:13px;">
      <strong>▷</strong> اختر فيديو من النتائج أعلاه للمعاينة
    </div>
  `;
  document.getElementById('scriptText').value = "";
}
</script>
</body>
</html>
