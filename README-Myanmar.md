## sylbreak

မြန်မာဘာသာစကားကို တည်ဆောက်မှုဘာသာဗေဒ (structural linguistics) အရ ခွဲခြမ်းစိတ်ဖြာမည်ဆိုပါက အောက်ပါအစီအစဉ်အဖြစ် မြင်နိုင်ပါသည်။ 

```text
အနက်ပေးသံစဉ်
(toneme)
|
|
| ----> ဝဏ္ဏ   -----> သဒ္ဒါရုပ်ရင်း -----> စကားလုံး -----> စကားစု -----> ဝါကျငယ် (သို့) ဝါကျ
|     (syllable)    (morpheme)       (word)       (phrase)    (clause or sentence)
|
အနက်ပေးသံရင်း
(phoneme)
```
<p align="justify">
sylbreak ပရိုဂရမ်က Unicode encoding နဲ့ (ဥပမာ Myanmar3 ဖောင့်၊ Padauk ဖောင့်များ နဲ့ ရိုက်ထားတဲ့စာတွေ) သိမ်းထားတဲ့ စာကြောင်းတွေကို ဝဏ္ဏ အစိတ်အပိုင်းယူနစ် (syllable) များအဖြစ် ခွဲပေးနိုင်ပါသည်။ ဒီဝဏ္ဏအစိတ်အပိုင်းယူနစ်တွေအဖြစ်ခွဲတဲ့ကိစ္စက Natural Language Processing (NLP) လို့ခေါ်တဲ့ သုတေသန မှာ အလွန်အရေးကြီးပါသည်။ NLP သုတေသနဆိုတာကို မြန်မာလိုလွယ်လွယ်ရှင်းပြရမယ်ဆိုရင်၊ ပရိုဂရမ်ဘာသာစကားတွေမဟုတ်တဲ့ ကျွန်တော်တို့ နေ့စဉ်သုံးနေကြတဲ့ သဘာဝဘာသာစကားတွေနဲ့ ပတ်သက်တဲ့လုပ်ငန်းတွေကို ကွန်ပျူတာမှာအသုံးပြုနိုင်အောင်၊ ကွန်ပျူတာကနားလည်အောင်ကြိုးစားနေကြတဲ့ သုတေသန ဖြစ်ပါသည်။ ဘာကြောင့် ဒီလို ဝဏ္ဏအစိတ်အပိုင်းယူနစ်တွေအဖြစ်ခွဲတဲ့ကိစ္စက အရေးကြီးသလဲဆိုရင် အထူးသဖြင့် မြန်မာစာကဲ့သို့သော ဘာသာစကား (syllabic language) တွေရဲ့ စာလုံးတလုံးချင်းစီက ဝဏ္ဏတွေနဲ့ ပေါင်းစပ်ထားတာဖြစ်လို့ပါ။
</p>

```text
ဥပမာ။ ။

ကျောင်း + သား -----> ကျောင်းသား
အ + တွေး + အ + ခေါ် -----> အတွေးအခေါ်
တက် + က + သိုလ် -----> တက္ကသိုလ်
```
<p align="justify">
NLP သုတေသန အလုပ်တွေထဲက တခုဖြစ်တဲ့ Romanization (ဘာသာစကားတခုက စာလုံးတွေကို လက်တင်စာအဖြစ်ပြောင်းလဲမှု) လို မြန်မာစာလုံးတွေကို အင်္ဂ﻿လိပ်စာလုံးနဲ့ ရေးတဲ့ ကိစ္စမျိုး (ငါးပိ ---> ngapi)၊ မြန်မာစာကြောင်းတွေကို ကွန်ပျူတာက အသံထွက်ဖတ်ပေးနိုင်အောင်ပြင်ဆင်ရတဲ့အလုပ် (Text to speech)၊ နောက်ပြီး စာလုံးပေါင်းမှားနေသလားဆိုတာကို ကွန်ပျူတာက စစ်ဆေးပေးနိုင်အောင်ပြင်ဆင်ကြရတဲ့ အလုပ်တွေ (spelling checking) အတွက်က ဝဏ္ဏအစိတ်အပိုင်းယူနစ်တွေက အရေးကြီးပါသည်။ 
</p>

<p align="justify">
သို့သော် ပါဠိပါဌ်ဆင့် စာလုံးတွေနဲ့ လက်တွေ့အလုပ်လုပ်တဲ့ အခါမှာတော့၊ အထက်မှာ ကျွန်တော်က တက္ကသိုလ်ဆိုတဲ့ စာလုံးကို တက်၊ က၊ သိုလ်၊ ဆိုပြီးဖြတ်ပြထားခဲ့ပေမဲ့၊  အဲဒီလိုမဖြတ်ပဲ တက္က နဲ့ သိုလ် ဆိုပြီးဖြတ်တာမျိုးက ပိုအဆင်ပြေတာမျိုးရှိကြောင်းကိုလဲ သိစေချင်ပါသည်။
ဥပမာ ကျွန်တော် ၅နှစ်ကျော် ဆက်တိုက်လုပ်ခဲ့တဲ့ ကွန်ပျူတာကိုသုံးပြီး ဘာသာစကား တစ်ခုကနေ တခြားဘာသာစကားတခုဆီကို ဘာသာပြန်တဲ့သုတေသနမှာဆိုရင် တက္က နဲ့ သိုလ် ဆိုတဲ့ ပုံစံမျိုးနဲ့ပဲ ဖြတ်ပြီးလုပ်ခဲ့ပါတယ်။ မဟုတ်ရင် တည်ဆောက်ခဲ့တဲ့ ဘာသာပြန်ပေးတဲ့ မိုဒယ် (machine translation model) ကထွက်လာတဲ့ မြန်မာ ပါဠိစာလုံးတွေကို ပြန်ပြီး နဂိုပုံစံဖြစ်တဲ့  ပါဌ်ဆင့်အဖြစ်ပြန်ဆင့်ပေးရတဲ့ အလုပ်လိုအပ်လို့ပါ။ လက်ရှိ sylbreak ပရိုဂရမ်မှာလဲ ပါဌ်ဆင့်စာလုံးတွေကို အသေးစိတ်မဖြတ်ထားပါ။
အသေးစိတ်ဖြတ်တာကလဲ မခက်ခဲပါ။ sylbreak ပရိုဂရမ်ကထွက်လာတဲ့ ဝဏ္ဏစာလုံးခွဲတွေကို နောက်တဆင့် စစ်ဆေးယူတဲ့ ကိစ္စပဲလိုအပ်တာပါ။ 
</p>

<p align="justify">
စိတ်ဝင်စားဖို့ ကောင်းတဲ့အချက်က မြန်မာစာဝဏ္ဏတွေကို မှန်မှန်ကန်ကန်ဖြတ်နိုင်အောင် သုတေသနလုပ်ခဲ့ကြတာတွေ အတော်များများ ရှိခဲ့ကြပါသည်။ ကျွန်တော်သိရသလောက်ဆိုရင် စာတမ်းတွေလည်း ၃စောင်နဲ့ အထက်မှာရှိတယ်လို့ ထင်ပါသည်။ ကျွန်တော်အပါအဝင်ပါပဲ အများစုက rule-based (ဥပမာ finite state automata modeling) လို့ခေါ်တဲ့ ဥပဒေသကို သတ်မှတ်ပြီး၊ လုပ်ခဲ့ကြပါသည်။  ဖြတ်လို့ရတဲ့နည်းတွေ ရှိခဲ့သော်လည်း  ပရိုဂရမ်မာတွေက လွယ်လွယ်ကူကူနဲ့ ယူသုံးလို့ရနိုင်တဲ့အဆင့်အထိ မရရှိခဲ့သေးပါ။  သို့သော် ကျွန်တော်က အမျိုးမျိုးစမ်းကြည့်ရင်းနဲ့သွားတွေ့တာက၊ ကျွန်တော်တို့ မြန်မာစာဝဏ္ဏတွေကို Unicode နဲ့သာရေးပြီး သိမ်းထားရင် Regular Expression (RE) တိုတို တကြောင်းထဲနဲ့ ဖြတ်ပေးနိုင်တယ်ဆိုတာကိုပါ။ RE က ၁၉၅၀ ဝန်းကျင်မှာ သင်္ချာပညာရှင် ဒေါက်တာ Stephen Cole Kleene (https://en.wikipedia.org/wiki/Stephen_Cole_Kleene) ကတင်ခဲ့တဲ့ ပရိုပိုဇယ် regular language ဆိုတဲ့ အယူအဆပါ၊ လိုချင်တဲ့ စာလုံးတွေ၊ စာကြောင်းတွေကို တိုက်စစ်တဲ့ နေရာမှာ အသုံးများပြီး၊ ကွန်ပျူတာ သိပ္ပံလောကမှာ မသိတဲ့သူ မရှိလောက်အောင်ကို အရေးပါပါသည်။ REကို ကွန်ပျူတာပရိုဂရမ်မာတွေ၊ လင်းနစ် (Linux) သမားတွေအားလုံးကလည်း အကျွမ်းတဝင်ရှိကြပါသည်။ ကျွန်တော် အဓိကပေးချင်တဲ့ message ကလည်း RE သုံးပြီး လွယ်လွယ်နဲ့ ဖြတ်လို့ရပါတယ် ဆိုတဲ့ အချက်ကိုပါ။ 
</p>

<p align="justify">
sylbreak ပရိုဂရမ်ကို မြန်မာစာပေဖွံဖြိုးတိုးတက်ဖို့ ကြိုးစားလုပ်ဆောင်နေကြတဲ့ မြန်မာစာ NLP သုတေသနသမားများ၊ ကျောင်းသားများ၊ ပရိုဂရမ်မာများ အားလုံးကို ဝေမျှပါတယ်။ ကျွန်တော်ရဲ့ sylbreak ပရိုဂရမ်ကို ယူသုံးမှ မဟုတ်ပါဘူး။ အောက်ပါ RE ကို ကိုယ့်ရဲ့ ပရိုဂရမ်မင်းဘာသာစကား တခုခုမှာ (Java, Python, C++, Visual Basic etc.) ထည့်သုံးတာမျိုးလဲ လုပ်နိုင်ပါသည်။
</p>

```perl
$line =~ s/((?<!$ssSymbol)[$myConsonant](?![$aThat$ssSymbol])|[$enChar$otherChar])/$sep$1/g;
```
<p align="justify">
အထက်ပါ RE က text processing မှာ အရမ်းအသုံးဝင်တဲ့ perl ပရိုဂရမ်မင်း ဘာသာစကားနဲ့ ရေးသားထားပါသည်။ 
အဓိက အရေးကြီးတဲ့ပွိုင့်က ဝင်လာတဲ့ စာကြောင်းတွေကို စစ်တဲ့ အခါမှာ၊ ပါဌ်ဆင့် သင်္ကေတဖြစ်တဲ့ (Unicode no. U1039) နောက်ကလိုက်တဲ့ ဗျည်းမဟုတ်ပဲ၊ အဲဒီဗျည်းရဲ့နောက်မှာလဲ ပါဌ်ဆင့် သင်္ကေတ (Unicode no. U1039) (သို့) အသတ် (Unicode no. U103A) မလိုက်ဘူး ဆိုရင်၊ အဲဒီဗျည်း ရဲ့ရှေ့မှာ ဖြတ်သားတဲ့အမှတ်အသား (ဥပမာ space (သို့) | (သို့) / စာလုံးမျိုး) ထည့်နိုင်တယ် ဆိုတဲ့ အချက်ပါ။
</p>

<img src="https://github.com/ye-kyaw-thu/sylbreak/blob/master/visualization-of-sylBreak-RE.png" alt="Visualization of sylbreak RE" width="812x180"/>
<p align="center"> Fig. sylbreak မှာ သုံးထားတဲ့ Regular Expression </p>

<p align="justify">
အသုံးပြုတဲ့ အခါမှာသာ ဒီ Github link: (https://github.com/ye-kyaw-thu/sylbreak) ကို မှီငြမ်းထားကြောင်းကို ကျေးဇူးပြုပြီး ဖော်ပြပေးစေချင်ပါသည်။ 
</p>

<p align="justify"> 
နောက် နှစ်အနည်းငယ်ကြာတဲ့ အခါမှာ လက်ရှိမြန်မာစာဆိုဒ်တွေ၊ သတင်းမီဒီယာဆိုဒ်တွေမှာ တွေ့နေရတဲ့ စာကြောင်းတွေရဲ့ အဆုံးပိုင်းတွေမှာ ပြတ်ချင်သလို၊ ပြတ်နေကြတဲ့၊ အရမ်းကို ကြည့်ရဆိုးတဲ့ မြန်မာဝဏ္ဏတွေလည်း လျော့ကျသွားလိမ့်မယ်လို့ ယူဆလျှက်။  
</p>


ရဲကျော်သူ@Lab

---

### Demo/Explanation

ICCA 2023 မှာ published လုပ်ထားတဲ့ စာတမ်း [An Algorithm for Myanmar Syllable Segmentation based on the Official Standard Myanmar Unicode Text](https://ieeexplore.ieee.org/document/10181391) မှာ sylbreak က အသတ်နဲ့ အောက်ကမြစ် တွဲပါနေတဲ့ ဗျည်းတချို့ကို syllable မဖြစ်ပေးနိုင်ဘူးလို့ မှားရေးထားတာကို ဖတ်လိုက်ရလို့ sylbreak tool က မြန်မာစာကို Unicode order အတိုင်းသာ ရိုက်ထည့်ထားရင် မှန်မှန်ကန်ကန် ဖြတ်ပေးနိုင်ကြောင်း ရှင်းပြထားပါတယ်။ ပြီးတော့ မြန်မာစာ စာလုံးတွေရိုက်ကြတဲ့အခါမှာ typing order တွေကို ဂရုစိုက်ဖို့လိုကြောင်းနဲ့ မြန်မာစာ NLP သုတေသန လုပ်နေကြတဲ့ သူတွေအနေနဲ့က Unicode encoding နဲ့ normalization ကိစ္စတွေကိုလည်း ဂဃနဏ သိထားဖို့ လိုအပ်ကြောင်းကို ရှင်းပြထားတဲ့ ဗီဒီယိုပါ။  

Video Link: [https://vimeo.com/864665740?share=copy](https://vimeo.com/864665740?share=copy)

### မှီငြမ်း ထားသော စာအုပ်၊ စာတမ်း၊ လင့်(ခ်)များ

1. ဒေါက်တာ သိန်းထွန်း၊ လေလှိုင်းသဒ္ဒဗေဒနှင့် မြန်မာစကားသံ ပြောင်းလဲမှုစနစ်
2. Romanization: https://en.wikipedia.org/wiki/Romanization
3. Myanmar Unicode: http://unicode.org/charts/PDF/U1000.pdf
4. Syllable segmentation algorithm of Myanmar text: http://gii2.nagaokaut.ac.jp/gii/media/share/20080901-ZMM%20Presentation.pdf
5. Zin Maung Maung and Yoshiki Makami,"A rule-based syllable segmentation of Myanmar Text", in Proceeding of the IJCNLP-08 workshop of NLP for Less Privileged Language, January, 2008, Hyderabad, India, pp. 51-58. [Paper](https://github.com/ye-kyaw-thu/sylbreak/blob/master/reference/I08-3010.pdf)
6. Tin Htay Hlaing. 2012. Manually constructed context-free grammar for Myanmar syllable structure. in Proceedings of the Student Research Workshop at the 13th Conference of the European Chapter of the Association for Computational Linguistics (EACL '12). Association for Computational Linguistics, Stroudsburg, PA, USA, 32-37. [Paper](https://github.com/ye-kyaw-thu/sylbreak/blob/master/reference/E12-3004.pdf)
7. Ye Kyaw Thu, Andrew Finch, Yoshinori Sagisaka and Eiichiro Sumita, "A Study of Myanmar Word Segmentation Schemes for Statistical Machine Translation", in Proceedings of the 11th International Conference on Computer Applications (ICCA 2013), February 26~27, 2013, Yangon, Myanmar, pp. 167-179. [Paper](https://github.com/ye-kyaw-thu/sylbreak/blob/master/reference/my2Others-CameraReady.pdf)
8. Ye Kyaw Thu, Andrew Finch, Win Pa Pa, and Eiichiro Sumita, "A Large-scale Study of Statistical Machine Translation Methods for Myanmar Language", in Proceedings of SNLP2016, February 10-12, 2016, Phranakhon Si Ayutthaya, Thailand. [Paper](https://github.com/ye-kyaw-thu/sylbreak/blob/master/reference/SNLP-3-A%20Large-scale%20Study%20of%20Statistical%20Machine%20Translation%20Methods%20for%20Myanmar%20Language.pdf)
9. Regular Expression: https://en.wikipedia.org/wiki/Regular_expression  
10. DebuggexBeter: https://www.debuggex.com/
11. Run UTN11 normalization on Myanmar text? [https://github.com/harfbuzz/harfbuzz/issues/494](https://github.com/harfbuzz/harfbuzz/issues/494)
