<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>٦٠ ثانية.. تفرق | بطاقة تثقيفية وتحدي</title>
  
  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@500;600;700;800;900&family=Tajawal:wght@400;500;700;800&display=swap" rel="stylesheet">
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <!-- Canvas Confetti CDN -->
  <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.9.2/dist/confetti.browser.min.js"></script>

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Tajawal', 'Cairo', 'sans-serif'],
            heading: ['Cairo', 'sans-serif'],
          },
          colors: {
            brand: {
              50: '#f5f3ff',
              100: '#ede9fe',
              200: '#ddd6fe',
              300: '#c4b5fd',
              400: '#a78bfa',
              500: '#8b5cf6',
              600: '#7c3aed',
              700: '#6d28d9',
              800: '#5b21b6',
              900: '#4c1d95',
            }
          },
          animation: {
            'fade-in': 'fadeIn 0.3s ease-out forwards',
            'bounce-short': 'bounceShort 0.5s ease-out 1',
          },
          keyframes: {
            fadeIn: {
              '0%': { opacity: '0', transform: 'translateY(6px)' },
              '100%': { opacity: '1', transform: 'translateY(0)' },
            },
            bounceShort: {
              '0%, 100%': { transform: 'scale(1)' },
              '50%': { transform: 'scale(1.03)' },
            }
          }
        }
      }
    }
  </script>

  <style>
    body {
      font-family: 'Tajawal', 'Cairo', sans-serif;
      background: radial-gradient(circle at 85% 15%, #ede9fe 0%, #f8fafc 45%, #eff6ff 100%);
      min-height: 100vh;
    }
    .custom-shadow {
      box-shadow: 0 10px 30px -10px rgba(124, 58, 237, 0.12), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
    }
  </style>
</head>

<body class="text-slate-800 antialiased selection:bg-brand-500 selection:text-white pb-20">

  <!-- Header -->
  <header class="w-full bg-white/85 backdrop-blur-md border-b border-slate-200/80 sticky top-0 z-30 transition-all">
    <div class="max-w-3xl mx-auto px-4 sm:px-6 h-16 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-600 to-indigo-500 flex items-center justify-center text-white shadow-md shadow-brand-500/25">
          <!-- Lightbulb Icon -->
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
          </svg>
        </div>
        <div>
          <h1 class="text-base sm:text-lg font-bold text-slate-900 leading-tight font-heading">٦٠ ثانية.. تفرق</h1>
          <p class="text-xs text-slate-500 font-medium">اقرأ المعلومة ثم أجب عن السؤال أدناه</p>
        </div>
      </div>

      <div class="flex items-center gap-2">
        <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full text-xs font-bold bg-brand-50 text-brand-700 border border-brand-200">
          <span class="w-2 h-2 rounded-full bg-brand-500 animate-pulse"></span>
          تحدي معرفي
        </span>
        <button id="btnHeaderShare" title="مشاركة التحدي" type="button" class="p-2 text-slate-600 hover:text-brand-600 hover:bg-brand-50 rounded-xl border border-slate-200 transition active:scale-95">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.684 13.342C8.886 12.938 9 12.482 9 12c0-.482-.114-.938-.316-1.342m0 2.684a3 3 0 110-2.684m0 2.684l6.632 3.316m-6.632-6l6.632-3.316m0 0a3 3 0 105.367-2.684 3 3 0 00-5.367 2.684zm0 9.316a3 3 0 105.368 2.684 3 3 0 00-5.368-2.684z" />
          </svg>
        </button>
      </div>
    </div>
  </header>

  <!-- Main Content Container -->
  <main class="max-w-3xl mx-auto px-4 sm:px-6 pt-6 space-y-6">

    <!-- Hero Card Banner -->
    <div class="relative overflow-hidden rounded-2xl bg-gradient-to-l from-brand-900 via-indigo-900 to-purple-950 text-white shadow-xl shadow-brand-900/15 border border-white/10 p-6 sm:p-8">
      <div class="absolute -top-16 -left-16 w-48 h-48 rounded-full bg-brand-500/20 blur-3xl pointer-events-none"></div>
      <div class="absolute -bottom-16 -right-16 w-48 h-48 rounded-full bg-cyan-500/20 blur-3xl pointer-events-none"></div>

      <div class="space-y-3 relative z-10">
        <div class="flex items-center gap-2">
          <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full text-xs font-bold bg-brand-500/90 text-white shadow-sm backdrop-blur-sm">
            <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
            معلومة اليوم
          </span>
          <span class="text-xs text-brand-200 font-medium">تثقيف صحي وقائي</span>
        </div>
        <h2 class="text-2xl sm:text-3xl font-extrabold font-heading text-white tracking-tight">
          ٦٠ ثانية.. تفرق
        </h2>
        <p class="text-sm text-slate-300 max-w-xl leading-relaxed">
          دقائق بسيطة من الوعي قد تغيّر مسار صحتك وجودة حياتك بالكامل.
        </p>
      </div>
    </div>

    <!-- 1. المعلومة التثقيفية (للقراءة فقط) -->
    <section class="bg-white rounded-2xl p-6 sm:p-7 custom-shadow border border-slate-200/80 relative overflow-hidden transition hover:border-brand-200">
      <div class="absolute top-0 right-0 left-0 h-1.5 bg-gradient-to-r from-brand-500 via-indigo-500 to-cyan-400"></div>

      <div class="flex items-start gap-4">
        <div class="w-12 h-12 rounded-xl bg-amber-50 border border-amber-200/80 flex items-center justify-center shrink-0 text-amber-600 shadow-sm mt-0.5">
          <!-- Information icon -->
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
          </svg>
        </div>

        <div class="flex-1 space-y-3">
          <div class="flex items-center justify-between border-b border-slate-100 pb-2">
            <h3 class="text-xs font-bold uppercase tracking-wider text-amber-700 flex items-center gap-1.5">
              <span>💡</span> المعلومة التثقيفية
            </h3>
            <span class="text-xs text-slate-400 bg-slate-100 px-2.5 py-0.5 rounded-full font-medium">اقرأ بتركيز</span>
          </div>
          <div class="text-slate-800 leading-relaxed text-base sm:text-lg font-normal whitespace-pre-line">مو كل الأبطال قوتهم الخارقة الطيران، أخصائي التثقيف الصحي (المدرب الصحي) يساعدك تفهم صحتك ويعلمك كيف تتبنى عادات صحية تمنعك من الأمراض.
قوته الحقيقية هي المعرفة التي تصنع فرقاً كبيراً في حياتك.</div>
        </div>
      </div>
    </section>

    <!-- 2. السؤال التفاعلي -->
    <section class="bg-white rounded-2xl p-6 sm:p-7 custom-shadow border border-slate-200/80 space-y-5">
      <div class="border-b border-slate-100 pb-4">
        <span class="inline-block text-xs font-bold text-indigo-600 bg-indigo-50 px-2.5 py-1 rounded-md mb-2">السؤال التفاعلي</span>
        <h3 class="text-lg sm:text-xl font-bold font-heading text-slate-900 leading-snug">
          إيش القوة الحقيقية لأخصائي التثقيف الصحي (المدرب الصحي)؟
        </h3>
      </div>

      <!-- خيارات الإجابة -->
      <div id="optionsListContainer" class="space-y-3">
        <!-- يتم إنشاؤها عبر الجافاسكريبت -->
      </div>

      <!-- صندوق التغذية الراجعة والنتيجة -->
      <div id="feedbackContainer" class="hidden rounded-xl p-4 sm:p-5 border transition-all duration-300 animate-fade-in">
        <div class="flex items-start gap-3.5">
          <div id="feedbackIconWrapper" class="w-8 h-8 rounded-full flex items-center justify-center shrink-0"></div>
          <div class="flex-1 space-y-1">
            <h4 id="feedbackTitle" class="font-bold text-base font-heading"></h4>
            <p id="feedbackText" class="text-sm leading-relaxed"></p>
          </div>
        </div>
      </div>

      <!-- شريط الإجراءات: زر المشاركة وزر إعادة المحاولة -->
      <div id="actionRowAfterAnswer" class="hidden pt-3 flex flex-wrap items-center justify-between gap-3">
        <button id="btnShareResult" class="inline-flex items-center gap-2 px-4 py-2.5 text-sm font-semibold text-white bg-brand-600 hover:bg-brand-700 rounded-xl transition shadow-sm active:scale-95">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.684 13.342C8.886 12.938 9 12.482 9 12c0-.482-.114-.938-.316-1.342m0 2.684a3 3 0 110-2.684m0 2.684l6.632 3.316m-6.632-6l6.632-3.316m0 0a3 3 0 105.367-2.684 3 3 0 00-5.367 2.684zm0 9.316a3 3 0 105.368 2.684 3 3 0 00-5.368-2.684z" />
          </svg>
          <span>مشاركة التحدي ورابط الصفحة</span>
        </button>
        <button id="btnResetQuestion" class="inline-flex items-center gap-2 px-4 py-2.5 text-sm font-semibold text-slate-700 hover:text-brand-700 bg-slate-100 hover:bg-brand-50 rounded-xl transition duration-200 border border-slate-200 active:scale-95 shadow-sm">
          <svg class="w-4 h-4 transition-transform group-hover:-rotate-90" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15"/>
          </svg>
          <span>إعادة التجربة</span>
        </button>
      </div>
    </section>

    <!-- Footer Note -->
    <footer class="pt-4 text-center">
      <p class="text-xs text-slate-400 font-medium">
        صفحة تفاعلية مخصصة للمشاركين للإجابة والتقييم اللحظي
      </p>
    </footer>

  </main>

  <!-- إشعار نسخ الرابط (Toast) -->
  <div id="toastNotification" class="fixed bottom-6 left-1/2 -translate-x-1/2 bg-slate-900/90 backdrop-blur-md text-white px-5 py-3 rounded-xl shadow-2xl flex items-center gap-2.5 text-sm font-medium z-50 transition-all duration-300 opacity-0 pointer-events-none translate-y-4">
    <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
    </svg>
    <span id="toastMessage">تم نسخ رابط التحدي بنجاح!</span>
  </div>

  <!-- Interactive Logic -->
  <script>
    // Audio feedback synth using Web Audio API (No external sound files required)
    const playSound = (isCorrect) => {
      try {
        const AudioContext = window.AudioContext || window.webkitAudioContext;
        if (!AudioContext) return;
        const ctx = new AudioContext();
        const now = ctx.currentTime;
        const osc = ctx.createOscillator();
        const gain = ctx.createGain();

        osc.connect(gain);
        gain.connect(ctx.destination);

        if (isCorrect) {
          // Cheerful chime (two-tone chord)
          osc.type = 'triangle';
          osc.frequency.setValueAtTime(523.25, now); // C5
          osc.frequency.setValueAtTime(659.25, now + 0.1); // E5
          osc.frequency.setValueAtTime(783.99, now + 0.2); // G5
          gain.gain.setValueAtTime(0.2, now);
          gain.gain.exponentialRampToValueAtTime(0.001, now + 0.5);
          osc.start(now);
          osc.stop(now + 0.5);
        } else {
          // Soft lower bump
          osc.type = 'sine';
          osc.frequency.setValueAtTime(220, now); // A3
          osc.frequency.exponentialRampToValueAtTime(146.83, now + 0.25); // D3
          gain.gain.setValueAtTime(0.18, now);
          gain.gain.exponentialRampToValueAtTime(0.001, now + 0.3);
          osc.start(now);
          osc.stop(now + 0.3);
        }
      } catch (e) {
        // Silently catch audio restrictions
      }
    };

    const cardData = {
      title: "٦٠ ثانية.. تفرق",
      badge: "معلومة اليوم",
      infoText: "مو كل الأبطال قوتهم الخارقة الطيران، أخصائي التثقيف الصحي (المدرب الصحي) يساعدك تفهم صحتك ويعلمك كيف تتبنى عادات صحية تمنعك من الأمراض.\nقوته الحقيقية هي المعرفة التي تصنع فرقاً كبيراً في حياتك.",
      question: "إيش القوة الحقيقية لأخصائي التثقيف الصحي (المدرب الصحي)؟",
      options: [
        "تشخيص الأمراض ووصف العلاج",
        "تمكين الناس من اتخاذ قرارات صحية أفضل",
        "إجراء العمليات الجراحية"
      ],
      correctIndex: 1,
      explanation: "اجعل أخصائي التثقيف الصحي (المدرب الصحي) جزءاً من حياتك الصحية!"
    };

    const arabicLetters = ['أ', 'ب', 'ج', 'د'];

    let hasAnswered = false;
    let selectedOptionIndex = null;

    function renderPage() {
      const container = document.getElementById('optionsListContainer');
      container.innerHTML = '';

      const feedbackBox = document.getElementById('feedbackContainer');
      const actionRow = document.getElementById('actionRowAfterAnswer');

      if (!hasAnswered) {
        feedbackBox.classList.add('hidden');
        actionRow.classList.add('hidden');
      }

      cardData.options.forEach((opt, idx) => {
        const btn = document.createElement('button');
        btn.type = 'button';
        btn.dataset.index = idx;

        let baseStyle = "w-full text-right p-4 rounded-xl border text-sm sm:text-base font-medium transition-all duration-200 flex items-center justify-between gap-3 ";

        if (!hasAnswered) {
          baseStyle += "border-slate-200 hover:border-brand-500 hover:bg-brand-50/70 hover:shadow-sm bg-white text-slate-800 cursor-pointer active:scale-[0.99]";
          btn.className = baseStyle;
          btn.innerHTML = `
            <div class="flex items-center gap-3.5">
              <span class="w-8 h-8 rounded-lg bg-slate-100 text-slate-600 font-bold text-sm flex items-center justify-center shrink-0 border border-slate-200">
                ${arabicLetters[idx] || (idx + 1)}
              </span>
              <span class="leading-snug">${opt}</span>
            </div>
            <div class="w-5 h-5 rounded-full border-2 border-slate-300 shrink-0"></div>
          `;
          btn.addEventListener('click', () => handleOptionSelect(idx));
        } else {
          const isCorrect = idx === cardData.correctIndex;
          const isUserSelection = idx === selectedOptionIndex;

          if (isCorrect) {
            baseStyle += "border-emerald-500 bg-emerald-50/90 text-emerald-950 font-bold shadow-sm";
          } else if (isUserSelection && !isCorrect) {
            baseStyle += "border-rose-400 bg-rose-50 text-rose-950 font-medium";
          } else {
            baseStyle += "border-slate-100 bg-slate-50 text-slate-400 opacity-60";
          }
          btn.className = baseStyle;
          btn.disabled = true;

          btn.innerHTML = `
            <div class="flex items-center gap-3.5">
              <span class="w-8 h-8 rounded-lg ${isCorrect ? 'bg-emerald-600 text-white' : (isUserSelection ? 'bg-rose-600 text-white' : 'bg-slate-200 text-slate-500')} font-bold text-sm flex items-center justify-center shrink-0 shadow-xs">
                ${arabicLetters[idx] || (idx + 1)}
              </span>
              <span class="leading-snug">${opt}</span>
            </div>
            <div class="shrink-0">
              ${isCorrect ? `
                <span class="inline-flex items-center gap-1 text-emerald-800 text-xs sm:text-sm font-bold bg-emerald-100/90 border border-emerald-300 px-3 py-1 rounded-full shadow-xs">
                  إجابة صحيحة ✓
                </span>` : (isUserSelection ? `
                <span class="inline-flex items-center gap-1 text-rose-800 text-xs sm:text-sm font-bold bg-rose-100/90 border border-rose-200 px-3 py-1 rounded-full shadow-xs">
                  إجابتك ✗
                </span>` : '')}
            </div>
          `;
        }

        container.appendChild(btn);
      });
    }

    function handleOptionSelect(idx) {
      if (hasAnswered) return;
      hasAnswered = true;
      selectedOptionIndex = idx;

      const feedbackBox = document.getElementById('feedbackContainer');
      const iconWrapper = document.getElementById('feedbackIconWrapper');
      const title = document.getElementById('feedbackTitle');
      const text = document.getElementById('feedbackText');
      const actionRow = document.getElementById('actionRowAfterAnswer');

      feedbackBox.classList.remove('hidden');
      actionRow.classList.remove('hidden');

      const isCorrect = idx === cardData.correctIndex;
      playSound(isCorrect);

      if (isCorrect) {
        // Trigger celebratory confetti effect
        try {
          if (typeof confetti === 'function') {
            confetti({
              particleCount: 85,
              spread: 70,
              origin: { y: 0.6 },
              colors: ['#8b5cf6', '#10b981', '#3b82f6', '#f59e0b']
            });
          }
        } catch(e) {}

        feedbackBox.className = "rounded-xl p-4 sm:p-5 border transition-all duration-300 bg-emerald-50 border-emerald-300 text-emerald-950 animate-fade-in";
        iconWrapper.className = "w-8 h-8 rounded-full bg-emerald-600 text-white flex items-center justify-center shrink-0 shadow-sm";
        iconWrapper.innerHTML = `
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7" />
          </svg>
        `;
        title.textContent = "إجابة صحيحة، أحسنت! 🎉";
        text.textContent = cardData.explanation;
      } else {
        feedbackBox.className = "rounded-xl p-4 sm:p-5 border transition-all duration-300 bg-rose-50 border-rose-300 text-rose-950 animate-fade-in";
        iconWrapper.className = "w-8 h-8 rounded-full bg-rose-600 text-white flex items-center justify-center shrink-0 shadow-sm";
        iconWrapper.innerHTML = `
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M6 18L18 6M6 6l12 12" />
          </svg>
        `;
        title.textContent = "إجابة غير صحيحة، حظاً أوفر!";
        const rightText = cardData.options[cardData.correctIndex];
        text.textContent = `الإجابة الصحيحة هي: "${rightText}". ${cardData.explanation}`;
      }

      renderPage();
    }

    function showToast(msg) {
      const toast = document.getElementById('toastNotification');
      const toastMsg = document.getElementById('toastMessage');
      if (msg) toastMsg.textContent = msg;
      toast.classList.remove('opacity-0', 'pointer-events-none', 'translate-y-4');
      toast.classList.add('opacity-100', 'translate-y-0');
      setTimeout(() => {
        toast.classList.add('opacity-0', 'pointer-events-none', 'translate-y-4');
        toast.classList.remove('opacity-100', 'translate-y-0');
      }, 3000);
    }

    function shareChallenge() {
      const shareData = {
        title: '٦٠ ثانية.. تفرق | بطاقة تثقيفية وتحدي',
        text: 'هل تعرف إيش القوة الحقيقية للمدرب الصحي؟ خض التحدي المعرفي الآن في ٦٠ ثانية!',
        url: window.location.href
      };

      if (navigator.share && navigator.canShare && navigator.canShare(shareData)) {
        navigator.share(shareData).catch(() => copyToClipboard(shareData.url));
      } else {
        copyToClipboard(shareData.url);
      }
    }

    function copyToClipboard(text) {
      const input = document.createElement('input');
      input.value = text;
      document.body.appendChild(input);
      input.select();
      try {
        document.execCommand('copy');
        showToast('تم نسخ رابط التحدي بنجاح!');
      } catch (e) {
        showToast('تم تجهيز الرابط للمشاركة');
      }
      document.body.removeChild(input);
    }

    window.addEventListener('DOMContentLoaded', () => {
      renderPage();

      document.getElementById('btnResetQuestion').addEventListener('click', () => {
        hasAnswered = false;
        selectedOptionIndex = null;
        renderPage();
      });

      const headerShareBtn = document.getElementById('btnHeaderShare');
      if (headerShareBtn) headerShareBtn.addEventListener('click', shareChallenge);

      const actionShareBtn = document.getElementById('btnShareResult');
      if (actionShareBtn) actionShareBtn.addEventListener('click', shareChallenge);
    });
  </script>
</body>
</html>
