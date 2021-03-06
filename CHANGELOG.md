### [@coreui/react](https://coreui.io/) changelog

##### `v2.1.3`
- chore: update `@coreui/coreui` to `^2.1.5`
- chore: update `reactstrap` to `^7.0.2`
- chore: update `react-perfect-scrollbar` to `^1.4.4`
- chore: update `react-router-dom` to `^4.3.1`
- chore: update `eslint` to `^5.12.0`
- chore: update `eslint-plugin-react` to `^7.12.3`

##### `v2.1.2`
- refactor: remove `element-closest` dependency issue #37 #50
- chore: update `core-js` to `2.6.1`
- chore: update `enzyme` to `3.8.0`
- chore: update `enzyme-adapter-react-16` to `1.7.1`
- chore: update `eslint` to `5.10.0`
- chore: update `react` to `16.7.0`
- chore: update `react-dom` to `16.7.0`

##### `v2.1.1`
- chore: update `enzyme-adapter-react-16` to `1.7.0`
- chore: update `eslint` to `5.9.0`
- chore: update `react-dom` to `16.6.3`
- chore: update `react` to `16.6.3`

##### `v2.1.0`
- feat(SidebarNav): navLink `attributes` - optional JS object with valid JS API naming:
  - valid attributes: `rel`, `target`, `hidden`, `disabled`, etc...
  - item example:
    ```
    {
    name: 'Try CoreUI PRO',
    url: 'https://coreui.io/pro/react/',
    icon: 'cui-layers icons',
    variant: 'danger',
    attributes: { target: '_blank', rel: "noopener" },
    },
    ```
- update `@coreui/coreui` to `2.1.0` - sidebar-nav-link-disabled-*
- chore: update `react-perfect-scrollbar` to `1.4.2`
- chore: update `eslint` to `5.8.0`
- chore: update `react` to `16.6.0`
- chore: update `react-dom` to `16.6.0`
- chore(demo): style.css update to `@coreui/coreui v2.1.0`, navLink `disabled` example

##### `v2.0.9`
- feat(Sidebar): badge on parent dropdown - thanks @jeff-nz
- fix(SidebarNav): handleClick() target->currentTarget open
- chore(demo): style.css update to `@coreui/coreui v2.0.15`

##### `v2.0.8`
- refactor(SidebarMinimizer): extract `togglePs` method
- refactor(SidebarMinimizer): for use `togglePs` method
- fix(SidebarMinimizer): add `componentDidMount` with `togglePs`
- refactor(AsideToggler): extract `toggle` method
- fix(AsideToggler): add missing `defaultOpen` prop
- fix(Aside): deprecate `hidden` prop in v2 as conflicting with HTML5 `hidden` attribute
- fix(Aside): `displayBreakpoint` behaviour
- update `@coreui/coreui` to `^2.0.14`
- update `reactstrap` to `^6.5.0`
- update `enzyme` to `3.7.0`
- update `enzyme-adapter-react-16` to `1.6.0`

##### `v2.0.7`
- fix(SidebarNav): dirty fix for rtl ps scrollingX issue

##### `v2.0.6`
- update `@coreui/coreui` to `^2.0.12`
- update `@coreui/icons` to `0.3.0`
- update `react-perfect-scrollbar` to `^1.2.2`
- update `reactstrap` to `^6.4.0`
- update `babel-eslint` to `^10.0.1`
- update `enzyme` to `^3.6.0`
- update `enzyme-adapter-react-16` to `^1.5.0`
- update `eslint` to `^5.6.1`
- update `eslint-plugin-import` to `^2.14.0`
- update `eslint-plugin-react` to `^7.11.1`
- update `nwb` to `^0.23.0`
- update `react` to `^16.5.2`
- update `react-dom` to `^16.5.2`
- update `sinon` to `^5.1.1`

##### `v2.0.5`
- feat: hide onclick outside mobile sidebar
- refactor: toggle-classes force
- refactor: Shared/classes.js *Breakpoints
- refactor: element-closest IE polyfill added
- chore: dependencies update

##### `v2.0.4`
- refactor(Breadcrumb): fix for dynamic url like `/path/:id`
- chore: update `prop-types` to `^15.6.2

##### `v2.0.3`
- fix: rollback to @coreui/icons v0.2.0

##### `v2.0.2`
- fix: remove AppLayout export as not production ready
- chore: dependencies update
- fix(Switch): not updating on props change - thanks @IceOnFire

##### `v2.0.1`
- chore: dependencies update

##### `v2.0.0`
- chore: dependencies update
- refactor(demo): `@coreui/icons`

##### `v2.0.0-rc.1`
-fix: minimized sidebar scrollbar issue
