# PHP Foundations Course — Status

## Location: `\\wsl$\Ubuntu\home\practicalace\projects\php`
## Netlify URL: rays-php.netlify.app
## Last Updated: 2026-04-17
## Supplementary Pages: troubleshooting.html, glossary.html, cheat-sheet.html, common-errors.html

---

## Overview

**PHP Foundations** is a standalone PHP language course — the second step in the learning path:

```
MySQL Foundations (done, rays-mysql.netlify.app) → PHP Foundations → PHP & WordPress (existing, rays-php-wordpress.netlify.app)
```

### Rationale
- MySQL course covers all database fundamentals — this course can focus purely on PHP
- Students who already know SQL skip MySQL and start here
- PDO lessons connect directly to the MySQL databases students already built
- Clean prerequisite chain mirrors the htmlcss → htmljs pattern

---

## Course Structure: 24 Lessons / 7 Modules

### Module 1: Getting Started (3 lessons)
| # | Lesson | File | Duration | Difficulty |
|---|--------|------|----------|------------|
| 1 | What Is PHP? | lesson_01.html | 30 min | beginner |
| 2 | Setting Up Your Environment (LAMP Stack) | lesson_02.html | 45 min | beginner |
| 3 | PHP Syntax Basics | lesson_03.html | 45 min | beginner |

### Module 2: Core Language (4 lessons)
| # | Lesson | File | Duration | Difficulty |
|---|--------|------|----------|------------|
| 4 | Operators & Expressions | lesson_04.html | 40 min | beginner |
| 5 | Control Flow (if/else, switch, match) | lesson_05.html | 45 min | beginner |
| 6 | Loops (for, while, do-while, foreach) | lesson_06.html | 45 min | beginner |
| 7 | Functions | lesson_07.html | 50 min | beginner |

### Module 3: Data Structures (3 lessons)
| # | Lesson | File | Duration | Difficulty |
|---|--------|------|----------|------------|
| 8 | Arrays | lesson_08.html | 50 min | beginner |
| 9 | Array Functions | lesson_09.html | 45 min | intermediate |
| 10 | Strings & String Functions | lesson_10.html | 45 min | intermediate |

### Module 4: Web Fundamentals (3 lessons)
| # | Lesson | File | Duration | Difficulty |
|---|--------|------|----------|------------|
| 11 | Working with Forms ($_GET & $_POST) | lesson_11.html | 50 min | intermediate |
| 12 | Input Validation & Sanitization | lesson_12.html | 45 min | intermediate |
| 13 | File Handling & Includes | lesson_13.html | 45 min | intermediate |

### Module 5: State & OOP (4 lessons)
| # | Lesson | File | Duration | Difficulty |
|---|--------|------|----------|------------|
| 14 | Superglobals | lesson_14.html | 40 min | intermediate |
| 15 | Sessions & Cookies | lesson_15.html | 45 min | intermediate |
| 16 | Object-Oriented PHP — Classes & Objects | lesson_16.html | 50 min | intermediate |
| 17 | OOP — Inheritance, Interfaces & Traits | lesson_17.html | 50 min | intermediate |

### Module 6: Database Integration (4 lessons)
| # | Lesson | File | Duration | Difficulty |
|---|--------|------|----------|------------|
| 18 | Error Handling (try/catch, Exceptions) | lesson_18.html | 45 min | intermediate |
| 19 | PDO — Connecting to MySQL & Prepared Statements | lesson_19.html | 50 min | intermediate |
| 20 | PDO — CRUD, Transactions & Fetch Styles | lesson_20.html | 50 min | intermediate |
| 21 | Building a CRUD App (Mini Project) | lesson_21.html | 60 min | intermediate |

### Module 7: Real-World Skills (3 lessons)
| # | Lesson | File | Duration | Difficulty |
|---|--------|------|----------|------------|
| 22 | File Uploads & Email | lesson_22.html | 45 min | intermediate |
| 23 | Security Fundamentals (SQLi, XSS, CSRF) | lesson_23.html | 50 min | intermediate |
| 24 | Deployment, Next Steps & Best Practices | lesson_24.html | 30 min | beginner |

---

## Key Topics by Lesson

- **Lesson 1** — Server-side vs client-side, how PHP works, PHP's role in web development, history
- **Lesson 2** — LAMP stack verification (from MySQL course), PHP info page, Apache config, first PHP file
- **Lesson 3** — `<?php ?>` tags, variables, data types (string, int, float, bool, null), echo/print, comments, type juggling
- **Lesson 4** — Arithmetic, assignment, comparison, logical, string operators, operator precedence, ternary, null coalescing
- **Lesson 5** — if/elseif/else, switch, match (PHP 8), nested conditionals, truthy/falsy values
- **Lesson 6** — for, while, do-while, foreach, break, continue, nested loops, practical patterns
- **Lesson 7** — Function declaration, parameters, return values, default values, type hints, scope, anonymous functions, arrow functions
- **Lesson 8** — Indexed arrays, associative arrays, multidimensional arrays, array destructuring, spread operator
- **Lesson 9** — array_map, array_filter, array_reduce, sort/asort/ksort, array_merge, array_search, array_keys/values, in_array
- **Lesson 10** — strlen, strpos, substr, str_replace, strtolower/upper, trim, explode/implode, sprintf, heredoc/nowdoc
- **Lesson 11** — HTML forms, GET vs POST, $_GET, $_POST, form processing, multi-value inputs, sticky forms
- **Lesson 12** — filter_var, filter_input, htmlspecialchars, FILTER_VALIDATE_*, FILTER_SANITIZE_*, regex basics, error messages
- **Lesson 13** — file_get_contents, file_put_contents, fopen/fread/fwrite/fclose, include/require/include_once/require_once, __DIR__
- **Lesson 14** — $_SERVER, $_REQUEST, $_FILES, $_ENV, $_COOKIE, $_SESSION overview, practical uses
- **Lesson 15** — session_start, $_SESSION, session destruction, cookies with setcookie, login/logout pattern, remember me
- **Lesson 16** — Classes, properties, methods, $this, constructors, visibility (public/protected/private), static, constants
- **Lesson 17** — Inheritance (extends), method overriding, abstract classes, interfaces (implements), traits, namespaces, autoloading basics
- **Lesson 18** — try/catch/finally, Exception class, custom exceptions, error levels, set_error_handler, error_reporting
- **Lesson 19** — PDO connection, DSN, prepared statements (? and :named), bindParam/bindValue, fetchAll/fetch, error modes
- **Lesson 20** — INSERT/UPDATE/DELETE with PDO, transactions (beginTransaction/commit/rollback), fetch styles, rowCount, lastInsertId
- **Lesson 21** — Full CRUD mini-app: task manager with list, add, edit, delete, search — bringing everything together
- **Lesson 22** — $_FILES, move_uploaded_file, file type/size validation, multiple uploads; mail() function, basic email sending
- **Lesson 23** — SQL injection (why prepared statements matter), XSS (output escaping), CSRF tokens, password hashing (password_hash/verify), HTTPS
- **Lesson 24** — Free hosting deployment (InfinityFree), Composer intro, framework overview (Laravel/Symfony), REST APIs, where to go next

---

## Development Environment

### Local: LAMP Stack
- Ubuntu (WSL)
- Apache2 + PHP 8.x
- MySQL 8.x (already installed from MySQL Foundations course)
- phpMyAdmin
- Students work locally; deployment covered in Lesson 24

### Course Template
- Uses established template from course_template (already copied)
- Same CSS framework (styles/main.css), JS enhancements (js/course-enhancements.js, js/clipboard.js)
- Light/dark theme toggle, responsive nav, prev/next navigation
- Mermaid diagrams for visual concepts
- Code blocks with language-php class
- Exercises with hint/solution pattern, quizzes
- Breadcrumb: Home > Module X > Lesson N: Title

---

## Progress Tracker

- [x] Step 1 — Decide lesson counts and module breakdowns ✅
- [x] Step 2 — Scaffold course (index.html, course-config.json, copy template files) ✅
- [x] Step 3 — Build lessons sequentially (24 / 24) ✅
  - [x] Lesson 1: What Is PHP? ✅
  - [x] Lesson 2: Setting Up Your Environment ✅
  - [x] Lesson 3: PHP Syntax Basics ✅
  - [x] Lesson 4: Operators & Expressions ✅
  - [x] Lesson 5: Control Flow ✅
  - [x] Lesson 6: Loops ✅
  - [x] Lesson 7: Functions ✅
  - [x] Lesson 8: Arrays ✅
  - [x] Lesson 9: Array Functions ✅
  - [x] Lesson 10: Strings & String Functions ✅
  - [x] Lesson 11: Working with Forms ✅
  - [x] Lesson 12: Input Validation & Sanitization ✅
  - [x] Lesson 13: File Handling & Includes ✅
  - [x] Lesson 14: Superglobals ✅
  - [x] Lesson 15: Sessions & Cookies ✅
  - [x] Lesson 16: OOP — Classes & Objects ✅
  - [x] Lesson 17: OOP — Inheritance, Interfaces & Traits ✅
  - [x] Lesson 18: Error Handling ✅
  - [x] Lesson 19: PDO — Connecting to MySQL ✅
  - [x] Lesson 20: PDO — CRUD, Transactions & Fetch Styles ✅
  - [x] Lesson 21: Building a CRUD App ✅
  - [x] Lesson 22: File Uploads & Email ✅
  - [x] Lesson 23: Security Fundamentals ✅
  - [x] Lesson 24: Deployment, Next Steps & Best Practices ✅
- [x] Step 4 — Supplementary pages (troubleshooting, glossary, cheat sheet, common errors) ✅
- [x] Step 5 — Favicon creation ✅
- [x] Step 6 — Browser testing ✅
- [ ] Step 7 — Verify prev/next navigation links
- [x] Step 8 — Update Ray's House of Fun with course link ✅

---

## What to Do Next

**Step 6 Browser Testing Results (2026-04-17):**
- ✅ Lesson pages: hero banner, breadcrumbs, code blocks with Copy button, Mermaid diagrams all render correctly
- ✅ Dark mode: proper contrast, styled nav/footer/cards, theme toggle persists
- ✅ Mobile (375px): hamburger menu, responsive content, tables scroll horizontally
- ✅ Supplementary pages: cheat-sheet, troubleshooting, glossary, common-errors all render with proper hero/TOC/nav
- ✅ Lesson 24 bottom nav: "Previous: Security Fundamentals" + "Course Complete!" (no broken next link)
- ✅ Footer: copyright, Ray's House of Fun link, Contact link, Print Page link all present
- ⚠️ **INDEX.HTML STILL HAS TEMPLATE PLACEHOLDERS** — title says "[Course Title]", body shows placeholder "Key concept or skill", "Target audience", etc. The module listing works (reads from course-config.json) but all surrounding content is un-customized template text. **FIXED 2026-04-17** — index.html fully customized with PHP course content, learning path, prerequisites, resource links (cheat sheet, glossary, common errors, troubleshooting), and external references. Also updated MySQL course index.html to link to PHP Foundations (was "coming soon").

**Step 7: Verify prev/next navigation links**
1. Check all 24 lessons have correct prev/next links
2. Then the only remaining issue is the index.html customization

Note: Step 8 (Ray's House of Fun) is complete — PHP Foundations added to index, search, and updates pages.
