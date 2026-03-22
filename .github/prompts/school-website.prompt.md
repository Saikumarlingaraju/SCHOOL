---
description: "Generate pages and components for Siddhardha Convent High School website. Use when: building school website pages, creating HTML/Tailwind components, scaffolding the school site."
agent: "agent"
tools: [search, file]
---

# Siddhardha Convent High School — Website Generator

Generate website pages and components for **Siddhardha Convent High School** using the specification below. Build with **HTML, Tailwind CSS, and JavaScript**. Every page must be mobile-first, accessible, and SEO-optimized.

## School Info

- **Established**: 1984
- **Board**: Telangana State Board (BSE Telangana)
- **Classes**: Nursery – Class 10
- **Medium**: English & Telugu
- **Student Strength**: ~1200 students
- **Location**: Yadav Nagar, Malkajgiri, Hyderabad – 500047
- **Phone**: +91 9849190754
- **Facilities**: Library, Playground, Smart Classrooms, Transport, Computer Lab, Science Lab, Medical Room, Activity Hall
- **Focus**: Holistic student development through academics, sports, and co-curricular activities

## Design System

### Colors

| Token       | Name           | Hex       |
|-------------|----------------|-----------|
| primary     | Royal Blue     | `#1E3A8A` |
| secondary   | Golden Yellow  | `#F59E0B` |
| background  | Light Slate    | `#F8FAFC` |
| text        | Dark Gray      | `#1F2937` |
| accent      | Emerald        | `#10B981` |

### Typography

| Element   | Font    | Size  |
|-----------|---------|-------|
| H1        | Poppins | 48px  |
| H2        | Poppins | 36px  |
| H3        | Poppins | 28px  |
| Body      | Inter   | 18px  |
| Small     | Inter   | 14px  |

### Design Principles

- Clean, modern, mobile-first
- Large hero images with parallax scrolling
- Simple navigation with clear hierarchy
- Style inspiration: Apple Education, Cambridge School websites, international school UI
- Animations: scroll animations, hover effects, animated counters, image sliders, parallax backgrounds

## Site Map

```
Home
 ├── About (History, Vision, Principal Message)
 ├── Academics (Curriculum, Subjects, Teaching Methods)
 ├── Facilities (Library, Labs, Playground, Transport)
 ├── Activities (Clubs, Events)
 ├── Admissions (Process, Documents, Fees)
 ├── Gallery (Campus, Sports, Events, Annual Day, Class Activities)
 ├── News & Events (Announcements, Exam Schedules, Holiday List)
 └── Contact (Address, Map, Form)
```

Secondary Pages: Faculty, Student Life, Sports, Achievements, Alumni, Downloads, FAQ

Portal Pages: Student Portal, Parent Portal, Admin Dashboard

## Homepage Sections (in order)

1. **Hero**: Full-screen banner — school building/students image, title "Siddhardha Convent High School", tagline "Shaping Young Minds Since 1984", sub "Nursery to Class X | Telangana State Board". CTAs: Apply Now, Explore School, Contact Us. Parallax + floating shapes.
2. **Quick Highlights**: 4 icon cards — 40+ Years Legacy (graduation cap), 1200+ Students (school building), Nursery to Class X (books), Holistic Development (trophy).
3. **About**: Image left / text right. School overview paragraph. "Learn More" button.
4. **Academics**: 3 cards — Pre-Primary (Nursery, LKG, UKG), Primary (Class 1–5), High School (Class 6–10).
5. **Facilities**: Grid of 8 cards — Smart Classrooms, Library, Computer Lab, Science Lab, Playground, Transport, Medical Room, Activity Hall.
6. **Student Life**: Image grid — Sports Day, Annual Day, Science Fair, Cultural Programs, Competitions.
7. **Achievements**: Animated counters — 1200+ Students, 40+ Years Excellence, 100+ Events, 100% SSC Success.
8. **Gallery Preview**: Image slider, categories — Campus, Events, Sports, Competitions, Annual Day.
9. **News & Announcements**: Cards — Admissions Open 2026, Annual Day Celebration, SSC Results, Sports Competition.
10. **Admission Banner**: Big CTA — "Admissions Open 2026-27", "Enroll your child at Siddhardha Convent High School". Buttons: Apply Online, Contact Office.

## Page Specifications

### About Page
- History: Established 1984, quality education in Malkajgiri area
- Vision: Develop responsible citizens through quality education and strong moral values
- Mission: Academic excellence, creativity, leadership, discipline and values
- Principal Message: Photo, message text, signature

### Academics Page
- Curriculum: Telangana State Board
- Subjects: Mathematics, Science, English, Telugu, Social Studies, Computer Education
- Teaching Methods: Interactive classrooms, digital learning, practical experiments, group discussions

### Facilities Page
- Library: 500+ books, reference materials, reading space
- Computer Lab: Modern computers, internet access, basic coding education
- Playground: Volleyball, basketball, athletics, tennikoit

### Activities Page
- Clubs: Science Club, Literary Club, Arts Club, Sports Club
- Events: Annual Day, Sports Day, Science Exhibition, Cultural Fest

### Admissions Page
- Process: Fill Application → Submit Documents → Admission Confirmation
- Documents: Birth Certificate, Transfer Certificate, Previous Marks Memo, Passport Photos
- Fee: Approx ₹4,500 per year

### Gallery Page
Categories: Campus, Sports, Events, Annual Day, Class Activities

### News Page
Content types: School Announcements, Exam Schedules, Holiday List, Events

### Contact Page
- Address: Siddhardha Convent High School, Yadav Nagar, Malkajgiri, Hyderabad, Telangana 500047
- Phone: +91 9849190754
- Embedded Google Map
- Contact form (Name, Email, Phone, Message)

## Footer (all pages)

3 columns:
1. **School**: About, Admissions, Academics, Gallery, Contact
2. **Quick Links**: Student Portal, Parent Portal, Downloads, News
3. **Contact**: Yadav Nagar, Malkajgiri, Hyderabad

## Portal Features (advanced)

- **Student Portal**: Attendance, homework, results, notices
- **Parent Portal**: Fees, progress reports, attendance, notices
- **Admin Dashboard**: Manage students, admissions, gallery, news, teachers

## SEO Keywords

Best school in Malkajgiri, Siddhardha Convent High School, Schools in Yadav Nagar, State board schools Hyderabad

## Instructions for Generation

When generating a page or component:
1. Use semantic HTML5 elements
2. Apply Tailwind CSS utility classes matching the design system above
3. Include responsive breakpoints (mobile-first: sm, md, lg, xl)
4. Add appropriate `aria-` attributes for accessibility
5. Include SEO meta tags (title, description, Open Graph) on full pages
6. Use placeholder images with descriptive alt text (e.g., "Students studying in classroom")
7. Add scroll animations via Intersection Observer or AOS library
8. Keep JavaScript minimal and vanilla unless a library is specified
