# 📊 Getting Started — Angular Pivot Table Component (Syncfusion EJ2)

[![License](https://img.shields.io/badge/license-SEE%20LICENSE%20IN%20license-blue.svg)](https://www.syncfusion.com/content/downloads/syncfusion_license.pdf)
[![Angular](https://img.shields.io/badge/Angular-21.1.0-green.svg)](https://angular.io/)
[![Last Updated](https://img.shields.io/github/last-commit/SyncfusionExamples/angular-pivot-table-getting-started.svg)](https://github.com/SyncfusionExamples/angular-pivot-table-getting-started/commits)
[![Syncfusion Version](https://img.shields.io/badge/Syncfusion%20EJ2-*-green.svg)](https://www.syncfusion.com/angular-components/)
[![Node.js](https://img.shields.io/badge/Node.js-LTS-green.svg)](https://nodejs.org/)
[![npm](https://img.shields.io/badge/npm-v10%2B-blue.svg)](https://www.npmjs.com/)

> 🚀 **Angular quick-start template** demonstrating Syncfusion EJ2 `PivotView` (Pivot Table) with **Field List**, **Grouping Bar**, **Calculated Fields**, **Formatting**, and **Sorting** — includes sample data, CLI scripts, and production-ready configuration.

> **📺 Official Demo:** https://ej2.syncfusion.com/angular/demos/#/bootstrap5/pivot-table/default  
> **📚 Official Documentation:** https://ej2.syncfusion.com/angular/documentation/pivotview/getting-started

---

## 📑 Table of Contents

- [🔍 Overview](#-overview)
- [✨ Key Features](#-key-features)
- [🧭 Quick Start](#-quick-start)
- [🗂️ Project Structure](#-project-structure)
- [🎨 Theming & Styling](#-theming--styling)
- [🧩 Minimal Example](#-minimal-example)
- [⚙️ Configuration & Customization](#-configuration--customization)
- [🤝 Contributing](#-contributing)
- [📜 License & Support](#-license--support)

---

## 🔍 Overview

This repository provides a **production-ready starter template** for integrating Syncfusion's powerful `PivotView` (Pivot Table) component into your **Angular applications**. It demonstrates essential features including:

- ✅ Interactive Pivot Table with drag-and-drop functionality
- ✅ Dynamic Field List for runtime field configuration
- ✅ Grouping Bar for intuitive data organization
- ✅ Calculated Fields for custom data computations
- ✅ Data Formatting (currency, percentages, etc.)
- ✅ Multi-level Sorting and Filtering
- ✅ Responsive Design with Tailwind CSS styling

---

## ✨ Key Features

| Feature | Description | Benefit |
|---------|-------------|---------|
| 🎯 **Field List Interface** | Dynamically add, remove, and rearrange data fields at runtime | Empowers end-users to customize reports without code |
| 📊 **Grouping Bar** | Drag-and-drop fields between rows, columns, values, and filters | Intuitive data organization and real-time pivot manipulation |
| 🧮 **Calculated Fields** | Create custom formulas combining multiple data fields | Advanced data analysis and custom metrics |
| 💱 **Data Formatting** | Display values in currency, percentages, and custom formats | Professional presentation of numerical data |
| ↕️ **Multi-Level Sorting** | Sort by multiple fields with ascending/descending control | Enhanced data exploration capabilities |
| 🔗 **Advanced Filtering** | Filter by single or multiple criteria across all dimensions | Focused data analysis and drill-down exploration |
| 📱 **Responsive Design** | Adapts seamlessly to desktop, tablet, and mobile screens | Universal accessibility across devices |
| 🚀 **Server-Side Rendering (SSR)** | Full Angular SSR support out-of-the-box | SEO-friendly and faster initial page loads |
| ⚡ **Ivy Compilation** | Modern Angular Ivy rendering engine | Smaller bundle sizes and improved performance |
| 🎨 **Theme Support** | Multiple Tailwind and Bootstrap themes available | Consistent branding and visual customization |

---

## 🚀 Quick Start

### Prerequisites

Ensure you have the following installed on your system:

- **Node.js** (LTS version or higher) — [Download](https://nodejs.org/)
- **npm** (v10+) — Included with Node.js
- **Angular CLI** — Install globally: `npm install -g @angular/cli`
- **Visual Studio Code** — Optional but recommended — [Download](https://code.visualstudio.com/)

### Installation & Setup

```bash
# 1️⃣ Clone the repository
git clone https://github.com/SyncfusionExamples/angular-pivot-table-getting-started.git

# 2️⃣ Navigate to the project directory
cd angular-pivot-table-getting-started

# 3️⃣ Install dependencies
npm install

# 4️⃣ Start the development server
npm start
```

**🎉 Success!** Your application will open at `http://localhost:4200/` in your default browser.

### Additional Commands

```bash
# 🔨 Build for production
npm run build

# 👀 Build and watch for changes (development)
npm run watch

# 🧪 Run unit tests
npm test

# 🌐 Serve SSR version
npm run serve:ssr:my-app
```

---

## 🗂️ Project Structure

```
angular-pivot-table-getting-started/
├── 📄 angular.json
├── 📄 package.json
├── 📄 README.md
├── 📄 tsconfig.app.json
├── 📄 tsconfig.json
├── 📄 tsconfig.spec.json
├── 📁 public/
└── 📁 src/
  ├── 📄 index.html
  ├── 📄 main.ts
  ├── 📄 styles.css
  └── 📁 app/
    ├── 📄 app.config.ts
    ├── 📄 app.css
    ├── 📄 app.html
    ├── 📄 app.routes.ts
    ├── 📄 app.spec.ts
    └── 📄 app.ts
```

### Key Files Explained

| File | Purpose |
|------|---------|
| `src/main.ts` | Angular application bootstrap entry point |
| `src/app/app.component.ts` | Root component containing PivotView logic |
| `src/styles.css` | Global styles and Syncfusion CSS imports |
| `package.json` | NPM dependencies (includes Syncfusion EJ2 packages) |
| `angular.json` | Angular CLI configuration for builds and dev server |

---

## 🎨 Theming & Styling

### Global CSS Imports (`src/styles.css`)

Add Syncfusion theme CSS to your global styles:

```css
/* Tailwind3 Theme (Modern) */
@import '../node_modules/@syncfusion/ej2-base/styles/tailwind3.css';
@import '../node_modules/@syncfusion/ej2-buttons/styles/tailwind3.css';
@import '../node_modules/@syncfusion/ej2-dropdowns/styles/tailwind3.css';
@import '../node_modules/@syncfusion/ej2-grids/styles/tailwind3.css';
@import '../node_modules/@syncfusion/ej2-inputs/styles/tailwind3.css';
@import '../node_modules/@syncfusion/ej2-lists/styles/tailwind3.css';
@import '../node_modules/@syncfusion/ej2-navigations/styles/tailwind3.css';
@import '../node_modules/@syncfusion/ej2-popups/styles/tailwind3.css';
@import '../node_modules/@syncfusion/ej2-splitbuttons/styles/tailwind3.css';
@import '../node_modules/@syncfusion/ej2-angular-pivotview/styles/tailwind3.css';
```

### Available Themes

- 🎨 **tailwind3** — Modern Tailwind CSS v3 design system
- 🏢 **bootstrap5** — Bootstrap 5 professional styling
- 💎 **fluent2** — Microsoft Fluent Design System
- 🌙 **material3** — Google Material Design 3
- 🎭 **fabric** — Microsoft Fabric Design System

**Swap themes** by replacing the CSS import path:

```css
/* Switch to Bootstrap5 theme */
@import '../node_modules/@syncfusion/ej2-angular-pivotview/styles/bootstrap5.css';
```

---

## 🧩 Minimal Example

### Component Implementation (`src/app/app.component.ts`)

```typescript
import { Component, OnInit } from '@angular/core';
import { PivotViewModule, PivotFieldListModule } from '@syncfusion/ej2-angular-pivotview';
import { 
  IDataOptions, 
  IDataSet, 
  FieldListService, 
  CalculatedFieldService 
} from '@syncfusion/ej2-angular-pivotview';

@Component({
  selector: 'app-root',
  standalone: true,
  imports: [PivotViewModule, PivotFieldListModule],
  providers: [FieldListService, CalculatedFieldService],
  template: `
    <div style="height: 480px;">
      <ejs-pivotview 
        #pivotview 
        id='PivotView' 
        height='350' 
        [dataSourceSettings]="dataSourceSettings"
        [width]="width"
        allowCalculatedField="true"
        showFieldList="true">
      </ejs-pivotview>
    </div>
  `
})
export class AppComponent implements OnInit {
  public pivotData!: IDataSet[];
  public dataSourceSettings!: IDataOptions;
  public width?: string;

  ngOnInit(): void {
    this.pivotData = [
      { 
        Amount: 2100, 
        Country: "Canada", 
        Date: "FY 2005", 
        Product: "Bike", 
        Quantity: 22, 
        State: "Alberta" 
      },
      { 
        Amount: 1100, 
        Country: "Canada", 
        Date: "FY 2006", 
        Product: "Van", 
        Quantity: 32, 
        State: "Quebec" 
      },
      // ... more data items
    ];

    this.dataSourceSettings = {
      dataSource: this.pivotData,
      columns: [
        { name: 'Date', caption: 'Date' }, 
        { name: 'Product' }
      ],
      rows: [
        { name: 'Country' }, 
        { name: 'State' }
      ],
      values: [
        { name: 'Amount', caption: 'Sold Amount' }, 
        { name: 'Quantity', caption: 'Quantity' }
      ],
      filters: [],
      expandAll: false,
      enableSorting: true,
      formatSettings: [{ name: 'Amount', format: 'C0' }],
      drilledMembers: [{ name: 'Country', items: ['France'] }],
      calculatedFieldSettings: [
        { name: 'Total', formula: '"Sum(Amount)"+"Sum(Quantity)"' }
      ]
    };

    this.width = "100%";
  }
}
```

### Template Binding (`src/app/app.component.html`)

The component uses inline template binding. For external templates, create:

```html
<!-- app.component.html -->
<div style="height: 480px;">
  <ejs-pivotview 
    #pivotview 
    id='PivotView' 
    height='350' 
    [dataSourceSettings]="dataSourceSettings"
    [width]="width"
    allowCalculatedField="true"
    showFieldList="true">
  </ejs-pivotview>
</div>
```
---

## ⚙️ Configuration & Customization

### 1️⃣ Configuring Pivot Table Axes

The `dataSourceSettings` object defines how data is organized:

```typescript
dataSourceSettings: {
  // 📊 Data Source
  dataSource: this.pivotData,
  
  // 🎯 Row Fields (left vertical axis)
  rows: [
    { name: 'Country', caption: 'Country' },
    { name: 'State', caption: 'State' }
  ],
  
  // 📈 Column Fields (top horizontal axis)
  columns: [
    { name: 'Date', caption: 'Fiscal Year' },
    { name: 'Product', caption: 'Product Category' }
  ],
  
  // 💰 Value Fields (numeric aggregations)
  values: [
    { name: 'Amount', caption: 'Sales Amount', type: 'Sum' },
    { name: 'Quantity', caption: 'Units Sold', type: 'Sum' }
  ],
  
  // 🔗 Filter Fields (master filters)
  filters: [
    { name: 'Region', caption: 'Region' }
  ]
}
```

### 2️⃣ Enabling Interactive Features

```typescript
// Component properties for interactive features
showFieldList: true,              // ✅ Enable Field List UI
showGroupingBar: true,            // ✅ Enable Grouping Bar
allowCalculatedField: true,       // ✅ Allow user-defined calculated fields
enableSorting: true,              // ✅ Enable multi-level sorting
enableFiltering: true,            // ✅ Enable advanced filtering
allowDrillThrough: true,          // ✅ Enable drill-through to detail data
```

### 3️⃣ Module Injection for Advanced Features

```typescript
import { 
  PivotViewModule, 
  PivotFieldListModule,
  GroupingBarService,
  FieldListService,
  CalculatedFieldService 
} from '@syncfusion/ej2-angular-pivotview';

@Component({
  providers: [
    GroupingBarService,        // For drag-drop grouping bar
    FieldListService,          // For field list interface
    CalculatedFieldService     // For calculated field support
  ]
})
export class AppComponent { }
```

### 4️⃣ Applying Data Formatting

Format numeric values for better presentation:

```typescript
formatSettings: [
  { name: 'Amount', format: 'C0' },           // Currency: $1,234
  { name: 'Quantity', format: 'N2' },         // Number: 1,234.56
  { name: 'Percentage', format: 'P2' },       // Percentage: 12.34%
  { name: 'Date', format: 'yyyy-MM-dd' }      // Date: 2025-02-03
]
```

### 5️⃣ Calculated Fields Example

Create custom fields combining multiple data sources:

```typescript
calculatedFieldSettings: [
  {
    name: 'GrossSales',
    formula: '"Sum(Amount)"+"Sum(Tax)"'
  },
  {
    name: 'NetSales',
    formula: '"Sum(GrossSales)"-"Sum(Discount)"'
  }
]
```

---

## 🤝 Contributing

We welcome contributions! Please follow these guidelines:

### 1. Fork & Clone

```bash
git clone https://github.com/YOUR-USERNAME/angular-pivot-table-getting-started.git
cd angular-pivot-table-getting-started
```

### 2. Create Feature Branch

```bash
git checkout -b feature/your-feature-name
```

### 3. Make Changes & Commit

```bash
# Follow conventional commits
git commit -m "feat: add pivot table export to Excel functionality"
```

### 4. Push & Create Pull Request

```bash
git push origin feature/your-feature-name
```

### Code Style Guidelines

- ✅ Follow Angular style guide: https://angular.io/guide/styleguide
- ✅ Use TypeScript strict mode
- ✅ Include meaningful variable names
- ✅ Add JSDoc comments for complex functions
- ✅ Write unit tests for new features

### Commit Message Format

```
<type>(<scope>): <subject>

<body>

<footer>
```

Examples:
- `feat(pivot-table): add calculated field validation`
- `fix(field-list): resolve drag-drop positioning issue`
- `docs(getting-started): update installation steps`
- `test(pivot-view): add unit tests for sorting`

---

## 📜 License & Support

### License

This project is licensed under the **Syncfusion Essential Studio Community License** or **Commercial License**. Ensure you have appropriate licensing for your use case.

**Commercial License:** Contact [sales@syncfusion.com](mailto:sales@syncfusion.com)

📄 **Full License Agreement:** https://www.syncfusion.com/content/downloads/syncfusion_license.pdf

### Support & Resources

| Resource | Link |
|----------|------|
| 📚 **Documentation** | https://ej2.syncfusion.com/angular/documentation/pivotview/getting-started |
| 🎥 **Video Tutorials** | https://www.youtube.com/watch?v=HXTnI9XhVSw |
| 💬 **Community Forum** | https://www.syncfusion.com/forums/angular |
| 🐛 **Report Issues** | [GitHub Issues](https://github.com/SyncfusionExamples/angular-pivot-table-getting-started/issues) |
| 📧 **Commercial Support** | sales@syncfusion.com |

### Getting Help

1. 🔍 Check the [official documentation](https://ej2.syncfusion.com/angular/documentation/pivotview/getting-started)
2. 💬 Ask in [Syncfusion community forums](https://www.syncfusion.com/forums/angular)
3. 📧 Contact [Syncfusion support](mailto:sales@syncfusion.com) for enterprise assistance

---

## 🌟 Related Resources

### 📚 Syncfusion Angular Components

- [Angular Data Grid](https://www.syncfusion.com/angular-components/angular-grid) — Enterprise-grade data table
- [Angular Charts](https://www.syncfusion.com/angular-components/angular-charts) — 50+ chart types
- [Angular Scheduler](https://www.syncfusion.com/angular-components/angular-scheduler) — Event scheduling
- [Angular Reports](https://www.syncfusion.com/angular-components/angular-reports) — Business intelligence reporting

### 🔗 Complementary Examples

- [TypeScript Pivot Table](https://github.com/SyncfusionExamples/getting-started-with-the-typescript-pivot-table-component)
- [React Pivot Table](https://github.com/SyncfusionExamples/getting-started-with-the-react-pivot-table-component)
- [Vue Pivot Table](https://github.com/SyncfusionExamples/getting-started-with-the-vue2-pivot-table-component)

### 📚 Learning Resources

- [Angular Official Guide](https://angular.io/docs)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [Syncfusion UI Library](https://www.syncfusion.com/angular-components)

---