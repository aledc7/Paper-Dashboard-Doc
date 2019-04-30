## SRC FOLDER

### The src folder contains most of the application code. Here you can find all the css/js and vue components. 



```js
|-- src
    |   |-- App.vue
    |   |-- gloablComponents.js
    |   |-- globalDirectives.js
    |   |-- main.js
    |   |-- pollyfills.js
    |   |-- sidebarLinks.js
    |   |-- assets
    |   |   |-- sass
    |   |       |-- demo.scss
    |   |       |-- element_variables.scss
    |   |       |-- paper-dashboard.scss
    |   |       |-- paper
    |   |           |-- _alerts.scss
    |   |           |-- _animated-buttons.scss
    |   |           |-- _buttons.scss
    |   |           |-- _cards.scss
    |   |           |-- _carousel.scss
    |   |           |-- _chartist.scss
    |   |           |-- _chat-message.scss
    |   |           |-- _checkbox-radio.scss
    |   |           |-- _circlechart.scss
    |   |           |-- _collapse.scss
    |   |           |-- _dropdown.scss
    |   |           |-- _fixed-social-plugin.scss
    |   |           |-- _footers.scss
    |   |           |-- _forms.scss
    |   |           |-- _inputs.scss
    |   |           |-- _labels.scss
    |   |           |-- _media.scss
    |   |           |-- _misc.scss
    |   |           |-- _mixins.scss
    |   |           |-- _modal.scss
    |   |           |-- _navbars.scss
    |   |           |-- _pages.scss
    |   |           |-- _progress-bars.scss
    |   |           |-- _responsive.scss
    |   |           |-- _select.scss
    |   |           |-- _sidebar-and-main-panel.scss
    |   |           |-- _slider.scss
    |   |           |-- _social.scss
    |   |           |-- _switch.scss
    |   |           |-- _tables.scss
    |   |           |-- _tabs-navs-pagination.scss
    |   |           |-- _tags.scss
    |   |           |-- _timeline.scss
    |   |           |-- _tooltips-and-popovers.scss
    |   |           |-- _typography.scss
    |   |           |-- _variables.scss
    |   |           |-- mixins
    |   |           |   |-- _alerts.scss
    |   |           |   |-- _buttons.scss
    |   |           |   |-- _cards.scss
    |   |           |   |-- _chartist.scss
    |   |           |   |-- _icons.scss
    |   |           |   |-- _inputs.scss
    |   |           |   |-- _labels.scss
    |   |           |   |-- _navbars.scss
    |   |           |   |-- _sidebar.scss
    |   |           |   |-- _social.scss
    |   |           |   |-- _table-row.scss
    |   |           |   |-- _tabs.scss
    |   |           |   |-- _tags.scss
    |   |           |   |-- _transparency.scss
    |   |           |   |-- _vendor-prefixes.scss
    |   |           |-- plugins
    |   |               |-- _animate.scss
    |   |               |-- _chartist.scss
    |   |               |-- _fullcalendar.scss
    |   |               |-- _jquery.jvectormap.scss
    |   |               |-- _perfect-scrollbar.scss
    |   |-- components
    |   |   |-- Dashboard
    |   |   |   |-- Layout
    |   |   |   |   |-- Content.vue
    |   |   |   |   |-- ContentFooter.vue
    |   |   |   |   |-- DashboardLayout.vue
    |   |   |   |   |-- LoadingMainPanel.vue
    |   |   |   |   |-- SidebarSharePlugin.vue
    |   |   |   |   |-- TopNavbar.vue
    |   |   |   |-- Views
    |   |   |       |-- Charts.vue
    |   |   |       |-- Calendar
    |   |   |       |   |-- Calendar.vue
    |   |   |       |   |-- CalendarRoute.vue
    |   |   |       |-- Components
    |   |   |       |   |-- Buttons.vue
    |   |   |       |   |-- GridSystem.vue
    |   |   |       |   |-- Icons.vue
    |   |   |       |   |-- Notifications.vue
    |   |   |       |   |-- Panels.vue
    |   |   |       |   |-- SweetAlert.vue
    |   |   |       |   |-- Typography.vue
    |   |   |       |-- Dashboard
    |   |   |       |   |-- Overview.vue
    |   |   |       |   |-- Stats.vue
    |   |   |       |   |-- Stats
    |   |   |       |       |-- Task.vue
    |   |   |       |       |-- TaskList.vue
    |   |   |       |       |-- TimeLine.vue
    |   |   |       |       |-- TimeLineItem.vue
    |   |   |       |-- Forms
    |   |   |       |   |-- ExtendedForms.vue
    |   |   |       |   |-- RegularForms.vue
    |   |   |       |   |-- ValidationForms.vue
    |   |   |       |   |-- Wizard.vue
    |   |   |       |   |-- ValidationForms
    |   |   |       |   |   |-- LoginForm.vue
    |   |   |       |   |   |-- RegisterForm.vue
    |   |   |       |   |   |-- TypeValidationForm.vue
    |   |   |       |   |-- Wizard
    |   |   |       |       |-- FirstStep.vue
    |   |   |       |       |-- SecondStep.vue
    |   |   |       |-- Maps
    |   |   |       |   |-- API_KEY.js
    |   |   |       |   |-- FullScreenMap.vue
    |   |   |       |   |-- GoogleMaps.vue
    |   |   |       |   |-- VectorMaps.vue
    |   |   |       |   |-- VectorMapsPage.vue
    |   |   |       |   |-- WorldMap.vue
    |   |   |       |   |-- world_map.js
    |   |   |       |-- Pages
    |   |   |       |   |-- background-2.jpg
    |   |   |       |   |-- Lock.vue
    |   |   |       |   |-- Login.vue
    |   |   |       |   |-- Register.vue
    |   |   |       |   |-- TimeLinePage.vue
    |   |   |       |   |-- UserProfile.vue
    |   |   |       |   |-- UserProfile
    |   |   |       |       |-- EditProfileForm.vue
    |   |   |       |       |-- MembersCard.vue
    |   |   |       |       |-- UserCard.vue
    |   |   |       |-- Tables
    |   |   |           |-- ExtendedTables.vue
    |   |   |           |-- PaginatedTables.vue
    |   |   |           |-- RegularTables.vue
    |   |   |           |-- users.js
    |   |   |-- GeneralViews
    |   |   |   |-- NotFoundPage.vue
    |   |   |-- UIComponents
    |   |       |-- Dropdown.vue
    |   |       |-- Pagination.vue
    |   |       |-- Progress.vue
    |   |       |-- Switch.vue
    |   |       |-- Cards
    |   |       |   |-- ChartCard.vue
    |   |       |   |-- CircleChartCard.vue
    |   |       |   |-- StatsCard.vue
    |   |       |-- Inputs
    |   |       |   |-- Checkbox.vue
    |   |       |   |-- formGroupInput.vue
    |   |       |   |-- Radio.vue
    |   |       |-- SidebarPlugin
    |   |           |-- index.js
    |   |           |-- MobileMenu.vue
    |   |           |-- SideBar.vue
    |   |           |-- SidebarItem.vue
    |   |           |-- UserMenu.vue
    |   |-- routes
    |       |-- routes.js
    
    ```
    
