# Contributing Guidelines
## دليل المساهمة

<div align="center">

![Contributors Welcome](https://img.shields.io/badge/Contributors-Welcome-brightgreen)
![Arabic](https://img.shields.io/badge/Language-Arabic-green)
![English](https://img.shields.io/badge/Language-English-blue)

*Thank you for considering contributing to the Bilingual AI Prompt Pack!*

*شكراً لك على التفكير في المساهمة في مجموعة برومبتات الذكاء الاصطناعي ثنائية اللغة!*

</div>

---

## 🤝 How to Contribute | كيفية المساهمة

<table>
<tr>
<td width="50%">

### 🇺🇸 English

We welcome contributions from developers, content creators, educators, and AI enthusiasts worldwide. There are many ways to contribute:

*Types of Contributions:*
- Adding new prompt categories
- Improving existing prompts
- Translating prompts between languages
- Fixing documentation errors
- Suggesting new features
- Reporting bugs or issues

</td>
<td width="50%">

### 🇸🇦 العربية

نرحب بالمساهمات من المطورين ومنشئي المحتوى والمعلمين وعشاق الذكاء الاصطناعي في جميع أنحاء العالم. هناك طرق كثيرة للمساهمة:

*أنواع المساهمات:*
- إضافة فئات برومبت جديدة
- تحسين البرومبتات الموجودة
- ترجمة البرومبتات بين اللغات
- إصلاح أخطاء التوثيق
- اقتراح ميزات جديدة
- الإبلاغ عن الأخطاء أو المشاكل

</td>
</tr>
</table>

## 🚀 Getting Started | البدء

### Prerequisites | المتطلبات الأساسية

- GitHub account | حساب GitHub
- Basic knowledge of Markdown | معرفة أساسية بـ Markdown
- Understanding of prompt engineering | فهم هندسة البرومبتات

### Step-by-Step Process | العملية خطوة بخطوة

#### 1. Fork the Repository | انسخ المستودع

bash
# Click "Fork" button on GitHub
# اضغط زر "Fork" في GitHub


#### 2. Clone Your Fork | استنسخ نسختك

bash
git clone https://github.com/YOUR_USERNAME/bilingual-ai-prompt-pack.git
cd bilingual-ai-prompt-pack


#### 3. Create a Branch | أنشئ فرع جديد

bash
# For new prompts | للبرومبتات الجديدة
git checkout -b add-new-prompts

# For fixes | للإصلاحات
git checkout -b fix-documentation

# For features | للميزات الجديدة
git checkout -b feature-new-category


#### 4. Make Your Changes | قم بالتغييرات

Follow our [style guide](#-style-guide--دليل-التنسيق) and [quality standards](#-quality-standards--معايير-الجودة).

#### 5. Test Your Changes | اختبر تغييراتك

bash
# Validate prompts | تحقق من البرومبتات
npm run validate

# Test locally | اختبر محلياً
npm test


#### 6. Commit and Push | احفظ وارفع التغييرات

bash
git add .
git commit -m "Add: New marketing prompts in Arabic and English"
git push origin your-branch-name


#### 7. Create Pull Request | أنشئ طلب سحب

- Go to your fork on GitHub
- Click "New Pull Request"
- Fill out the template completely
- Wait for review

---

## 📝 Style Guide | دليل التنسيق

### Prompt Structure | هيكل البرومبت

Each prompt file should follow this structure:

markdown
# Category: [CATEGORY NAME]
## [Specific Prompt Title]

### English Version
**Purpose:** Brief description of what this prompt does
**Best for:** Target audience or use case


[Your English prompt here]


**Example Usage:**
[Show how to customize the prompt]

**Expected Output:**
[Describe what kind of response to expect]

### Arabic Version | النسخة العربية
**الغرض:** وصف موجز لما يفعله هذا البرومبت
**الأفضل لـ:** الجمهور المستهدف أو حالة الاستخدام


[البرومبت باللغة العربية هنا]


**مثال الاستخدام:**
[أظهر كيفية تخصيص البرومبت]

**النتيجة المتوقعة:**
[اوصف نوع الاستجابة المتوقعة]


### File Naming Convention | قواعد تسمية الملفات

- Use kebab-case: prompt-name.md
- Be descriptive: social-media-posts.md
- Avoid spaces and special characters
- Keep names under 50 characters

### Directory Structure | هيكل الدليل


prompts/
└── [category]/
    ├── english/
    │   └── specific-prompt.md
    └── arabic/
        └── specific-prompt.md


---

## 🎯 Quality Standards | معايير الجودة

### Prompt Requirements | متطلبات البرومبت

<table>
<tr>
<td width="50%">

*English Requirements:*
- ✅ Clear and specific instructions
- ✅ Appropriate context setting
- ✅ Defined output format
- ✅ Relevant constraints
- ✅ Professional language
- ✅ Tested for effectiveness
- ✅ Includes example usage
- ✅ Specifies target audience

</td>
<td width="50%">

*متطلبات العربية:*
- ✅ تعليمات واضحة ومحددة
- ✅ تحديد السياق المناسب
- ✅ تنسيق ناتج محدد
- ✅ قيود ذات صلة
- ✅ لغة احترافية
- ✅ مختبر للفعالية
- ✅ يتضمن مثال للاستخدام
- ✅ يحدد الجمهور المستهدف

</td>
</tr>
</table>

### Translation Guidelines | إرشادات الترجمة

- *Accuracy*: Maintain meaning across languages
- *Cultural Context*: Adapt for Arabic-speaking audience
- *Technical Terms*: Use appropriate Arabic technical vocabulary
- *Clarity*: Ensure instructions are equally clear in both languages

### دقة الترجمة | Translation Accuracy

- *الدقة*: الحفاظ على المعنى عبر اللغات
- *السياق الثقافي*: التكيف مع الجمهور الناطق بالعربية
- *المصطلحات التقنية*: استخدام المفردات التقنية العربية المناسبة
- *الوضوح*: التأكد من وضوح التعليمات بنفس الدرجة في كلا اللغتين

---

## 🔍 Review Process | عملية المراجعة

### What We Look For | ما نبحث عنه

1. *Prompt Quality*: Effectiveness and clarity
2. *Language Quality*: Grammar and style in both languages
3. *Completeness*: Both English and Arabic versions provided
4. *Documentation*: Proper formatting and examples
5. *Originality*: Unique and valuable contributions

### Review Timeline | الجدول الزمني للمراجعة

- *Initial Response*: Within 48 hours
- *Detailed Review*: 3-7 business days
- *Revisions*: As needed
- *Merge*: After approval and final checks

---

## 🐛 Bug Reports | بلاغات الأخطاء

### Before Reporting | قبل الإبلاغ

- Check existing issues
- Test the prompt thoroughly
- Gather relevant information

### Bug Report Template | قالب بلاغ الخطأ

markdown
**Prompt Category:** [e.g., Content Creation]
**Language:** [English/Arabic/Both]
**Issue Type:** [Bug/Enhancement/Question]

**Description:**
Clear description of the issue

**Steps to Reproduce:**
1. Step one
2. Step two
3. Step three

**Expected Behavior:**
What should happen

**Actual Behavior:**
What actually happens

**Additional Context:**
Any other relevant information


---

## 💡 Feature Requests | طلبات الميزات

We welcome suggestions for:
- New prompt categories
- Template improvements
- Tool integrations
- Documentation enhancements

Use our [feature request template](.github/ISSUE_TEMPLATE/feature_request.md).

---

## 📞 Getting Help | الحصول على المساعدة

### Communication Channels | قنوات التواصل

- *Issues*: For bugs and feature requests
- *Discussions*: For questions and general discussion
- *Email*: [your.email@example.com] for urgent matters

### Community Guidelines | إرشادات المجتمع

- Be respectful and inclusive
- Provide constructive feedback
- Help others when possible
- Follow our [Code of Conduct](CODE_OF_CONDUCT.md)

---

## 🏆 Recognition | التقدير

### Contributors Wall | جدار المساهمين

All contributors will be recognized in our:
- README.md contributors section
- Annual contributor highlights
- Special recognition for major contributions

### Contribution Types | أنواع المساهمات

We recognize various types of contributions:
- 📝 Content (prompts, documentation)
- 🐛 Bug fixes
- 🌍 Translations
- 💡 Ideas and suggestions
- 👥 Community support

---

## 📜 License | الترخيص

By contributing, you agree that your contributions will be licensed under the same [MIT License](LICENSE) that covers the project.

بالمساهمة، فإنك توافق على أن مساهماتك ستكون مرخصة تحت نفس [رخصة MIT](LICENSE) التي تغطي المشروع.

---

<div align="center">

*Thank you for making this project better! 🎉*

*شكراً لك لجعل هذا المشروع أفضل! 🎉*

</div>
