# 📋 IGEOS PRO X - DOCUMENT NUMBERING SYSTEM
## نظام ترقيم الوثائق الموحد

---

## **1. نظام الترقيم الأساسي**

### **الصيغة الرئيسية**
```
[BOOK].[CHAPTER].[SECTION].[SUBSECTION]-[REVISION]

مثال:
01.03.02.01-A
│   │   │   │  │
│   │   │   │  └─ الإصدار (A, B, C, ...)
│   │   │   └──── القسم الفرعي (01, 02, ...)
│   │   └──────── القسم الرئيسي (01, 02, ...)
│   └────────── الفصل (01, 02, ...)
└──────────── الكتاب (01, 02, ...)
```

---

## **2. ترقيم الكتب (BOOKS)**

```
01 = Governance & Corporate Structure ⭐ (Phase 1)
02 = Project Management Framework
03 = Technical Office Operations
04 = FIDIC Contracts Management
05 = Tender & Procurement
06 = Planning & Scheduling
07 = Cost Control & Budget
08 = Civil Engineering Standards
09 = Architectural Design
10 = Electrical Systems
11 = Mechanical Systems
12 = MEP Coordination
13 = Building Information Modeling (BIM)
14 = Quality Assurance & Control
15 = Health Safety & Environment
16 = Sustainability & Green Building
17 = Human Resources & Team Management
18 = Financial & Feasibility Studies
19 = Business Development & Marketing
20 = Corporate Operations Manual
```

---

## **3. ترقيم الفصول والأقسام**

### **مثال من Book 1 (الحوكمة)**

```
BOOK 01: Governance & Corporate Structure
├── CHAPTER 01: Corporate Structure (الهيكل التنظيمي)
│   ├── Section 01: Overview (نظرة عامة)
│   ├── Section 02: Organizational Chart (الهيكل التنظيمي)
│   ├── Section 03: Departments (الأقسام)
│   └── Section 04: Key Positions (المناصب الرئيسية)
│
├── CHAPTER 02: Roles & Responsibilities (الأدوار والمسؤوليات)
│   ├── Section 01: Executive Level
│   ├── Section 02: Management Level
│   ├── Section 03: Staff Level
│   └── Section 04: Support Functions
│
├── CHAPTER 03: Authorities & Powers (السلطات والصلاحيات)
│   ├── Section 01: Board of Directors
│   ├── Section 02: Executive Committee
│   ├── Section 03: Department Heads
│   └── Section 04: Decision Limits
│
└── CHAPTER 04: Operating Procedures (الإجراءات التشغيلية)
    ├── Section 01: Decision Making
    ├── Section 02: Approval Process
    ├── Section 03: Document Management
    └── Section 04: Communication Protocol
```

### **أمثلة على الترقيم الكامل**

```
01.01.01.01-A = Book 1, Chapter 1, Section 1, Subsection 1, Revision A
                الهيكل التنظيمي - نظرة عامة - أول نقطة

01.02.03.02-B = Book 1, Chapter 2, Section 3, Subsection 2, Revision B
                الأدوار والمسؤوليات - مستوى الإدارة - النقطة الثانية

01.04.02.01-C = Book 1, Chapter 4, Section 2, Subsection 1, Revision C
                الإجراءات - عملية الموافقة - النقطة الأولى
```

---

## **4. ترقيم الإصدارات (REVISIONS)**

### **منهجية الإصدارات**

```
Revision Letter System:
A = الإصدار الأول (First Release)
B = التصحيحات البسيطة (Minor Corrections)
C = التحديثات الصغيرة (Small Updates)
D = إضافات أو حذف محدود
...
Z = الإصدار النهائي قبل الإصدار الجديد

مثال:
01.01.01.01-A → 01.01.01.01-B → 01.01.01.01-C → 01.01.01.01-Z
```

### **إدارة الإصدارات في Git**

```
Version Format: IGEOS-X.Y.Z
X = Major Version (تغييرات كبيرة)
Y = Minor Version (إضافات جديدة)
Z = Patch Version (تصحيحات)

أمثلة:
IGEOS-1.0.0 = الإصدار الأول (Phase 1)
IGEOS-1.1.0 = إضافة كتاب جديد
IGEOS-1.0.1 = تصحيحات في Book 1
IGEOS-2.0.0 = جميع 20 كتاب كاملة
```

---

## **5. ترقيم النماذج والقوالب**

### **صيغة ترقيم النماذج**

```
[BOOK]-[TYPE]-[SEQUENCE]-[REVISION]

أمثلة:
01-ORG-001-A = Book 1, Template Type Organizational, Template 001, Revision A
01-FOR-002-B = Book 1, Form, Form 002, Revision B
01-CHK-003-C = Book 1, Checklist, Checklist 003, Revision C
```

### **أنواع النماذج (TYPES)**

```
ORG = Organizational Documents (وثائق تنظيمية)
FOR = Forms (نماذج)
CHK = Checklists (قوائم تحقق)
RPT = Reports (تقارير)
CTR = Contracts (عقود)
PRO = Procedures (إجراءات)
POL = Policies (سياسات)
GDE = Guidelines (مبادئ توجيهية)
```

### **أمثلة عملية**

```
01-ORG-001-A = Organizational Chart Template
01-FOR-001-A = Job Description Form
01-CHK-001-A = Roles & Responsibilities Checklist
01-CHK-002-B = Authorities Matrix Checklist
01-FOR-002-A = Decision Log Form
```

---

## **6. ترقيم الملفات في النظام**

### **هيكل مجلدات الملفات**

```
igeos-pro-x/
├── books/
│   ├── 01-governance/
│   │   ├── 01-01-corporate-structure/
│   │   │   ├── 01.01.01-overview.md
│   │   │   ├── 01.01.02-org-chart.md
│   │   │   └── 01.01.03-departments.md
│   │   ├── 01-02-roles-responsibilities/
│   │   └── ...
│   ├── 02-projects/
│   └── ...
├── templates/
│   ├── 01-governance/
│   │   ├── 01-ORG-001-Org-Chart.xlsx
│   │   ├── 01-FOR-001-Job-Description.docx
│   │   ├── 01-CHK-001-Roles-Checklist.docx
│   │   └── ...
│   ├── 02-projects/
│   └── ...
└── checklists/
    ├── 01-governance/
    │   ├── 01-CHK-001-Governance.docx
    │   ├── 01-CHK-002-Authorities.docx
    │   └── ...
    └── ...
```

---

## **7. جدول مرجعي سريع**

| المكون | الصيغة | مثال | الملاحظات |
|--------|--------|--------|----------|
| **كتاب** | XX | 01 | رقم بـ 2 خانة من 01-20 |
| **فصل** | XX | 03 | رقم بـ 2 خانة من 01-12 |
| **قسم** | XX | 02 | رقم بـ 2 خانة من 01-10 |
| **تقسيم فرعي** | XX | 01 | رقم بـ 2 خانة من 01-05 |
| **إصدار** | [A-Z] | A, B, C | حرف واحد |
| **نموذج** | XXX | 001, 002 | 3 خانات |

---

## **8. معايير التسمية في Git**

### **Branch Naming**
```
feature/01-book-governance
feature/templates/01-org-chart
fix/01.01.01-typo
release/igeos-1.0.0
```

### **Commit Messages**
```
[01.01.01-A] Initial corporate structure outline
[01-FOR-001-B] Update job description template
[Book-1-Complete] Finalize governance book
[Release-1.0.0] Complete Phase 1 delivery
```

---

## **9. التحقق من الامتثال**

### **قائمة التحقق**

- ✅ هل رقم الكتاب صحيح (01-20)؟
- ✅ هل رقم الفصل صحيح؟
- ✅ هل رقم القسم صحيح؟
- ✅ هل الإصدار محدث؟
- ✅ هل اسم الملف يتطابق مع الترقيم؟
- ✅ هل المسار المجلد صحيح؟
- ✅ هل هناك تعارض مع وثائق أخرى؟

---

## **10. نصائح عملية**

```
✅ ابدأ بـ -A دائماً للإصدار الأول
✅ اجعل الترقيم متسقاً في جميع الوثائق
✅ استخدم Git tags للإصدارات الرسمية
✅ حافظ على سجل بجميع التغييرات
✅ تحقق من الترقيم قبل النشر
```

---

**الحالة: ✅ FINAL**
الإصدار: 1.0 | آخر تحديث: 2026-01-01