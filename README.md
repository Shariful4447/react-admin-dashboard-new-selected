# React Admin Dashboard 


## Technology used
1. React
2. Material UI 
3. Formik
4. Yup
5. Nivo chart
6. Full-calendar
7. React-Pro-Sidebar



### This application consists of 
* Light & Dark Mode
* Dashboard Summary
* 3 Different Data Table Pages
* User Input Form Page  
* Calendar Integration
* FAQ Page
* 4 Different Charts



## Learning Context
* ...spread operator + conditional base object property loading at theme level
* introduce with css tool ==> [Pesticide][link]
* by array of object{text,icon}, construct side-menu
* row-column material-ui layout data display...
* usage of `data-grid` layout of `material ui`...
* path name become selected menu item, after refresh also...
* user input form validation `yup` checking...
* phone number regex pattern from input string...
* usage of `react-pro-sidebar@0.7.1` with its `css`...
* usage of `full-calendar` library...
* usage of `nivo chart` system...
* migrate experience from Vite to React, 
    * because Vite have some issus with full-calendar lib...

## In order to run 
* install node module with npm install
* start the application with npm start

## File & Folder Hierarchy

```
🟨
src
├── components
|   ├── BarChart.jsx
|   ├── GeographyChart.jsx
|   ├── Header.jsx
|   ├── index.js
|   ├── LineChart.jsx
|   ├── PieChart.jsx
|   ├── ProgressCircle.jsx
|   └── StatBox.jsx
|
├── constants
|   ├── contactsColumns.js
|   ├── faq.js
|   ├── inputFormFields.js
|   ├── inputFormValues.js
|   ├── invoicesColumns.js
|   ├── mockData.js
|   ├── mockGeoFeatures.js
|   ├── sidebarMenu.js
|   └── teamColumns.js
|
├── pages
|   |   Dashboard.jsx
|   |   index.js
|   |
|   ├── charts
|   |   ├── Bar.jsx
|   |   ├── Geography.jsx
|   |   ├── Line.jsx
|   |   └── Pie.jsx
|   |
|   ├── global
|   |   ├── SidebarMenu.jsx
|   |   ├── SidebarMenuItem.jsx
|   |   └── Topbar.jsx
|   |
|   ├── info
|   |   ├── Contacts.jsx
|   |   ├── Invoices.jsx
|   |   └── Team.jsx
|   |
|   └── inputs
|       ├── Calendars.jsx
|       ├── FAQ.jsx
|       └── InputForm.jsx
|
├── styles
|   ├── index.css
|   └── theme.js
|
├── App.jsx
└── index.js
🟨
```

```
tree /f
```


