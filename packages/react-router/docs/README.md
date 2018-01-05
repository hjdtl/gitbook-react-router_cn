# **中文文档**

版本：4.x

## 指南

  * [设计理念](/packages/react-router/docs/guides/Philosophy.md)
  * [快速开始](/packages/react-router/docs/guides/QuickStart.md)
  * [服务器渲染](/packages/react-router/docs/guides/ServerRendering.md)
  * [代码分割](/packages/react-router/docs/guides/CodeSplitting.md)
  * [滚动复位](/packages/react-router/docs/guides/ScrollRestoration.md)
  * [测试](/packages/react-router/docs/guides/Testing.md)
  * [集成 Redux](/packages/react-router/docs/guides/ReduxIntegration.md)
  * [静态路由](/packages/react-router/docs/guides/StaticRoutes.md)
  * [处理更新阻塞](/packages/react-router/docs/guides/DealingWithUpdateBlocking.md)

## API

  * [`<BrowserRouter>`](/packages/react-router/docs/api/BrowserRouter.md)
      - basename: string
      - getUserConfirmation: func
      - forceRefresh: bool
      - keyLength: number
      - children: node
  * [`<HashRouter>`](/packages/react-router/docs/api/HashRouter.md)
      - basename: string
      - getUserConfirmation: func
      - hashType: string
      - children: node
  * [`<Link>`](/packages/react-router/docs/api/Link.md)
      - to: string
      - to: object
      - replace: bool
  * [`<NavLink>`](/packages/react-router/docs/api/NavLink.md)
      - activeClassName: string
      - activeStyle: object
      - exact: bool
      - strict: bool
      - isActive: func
      - location: object
  * [`<Prompt>`](/packages/react-router/docs/api/Prompt.md)
  * [`<MemoryRouter>`](/packages/react-router/docs/api/MemoryRouter.md)
      - initialEntries: array
      - initialIndex: number
      - getUserConfirmation: func
      - keyLength: number
      - children: node
  * [`<Redirect>`](/packages/react-router/docs/api/Redirect.md)
      - to: string
      - to: object
      - push: bool
      - from: string
  * [`<Route>`](/packages/react-router/docs/api/Route.md)
      - Route render methods
      - Route props
      - component
      - render: func
      - children: func
      - path: string
      - exact: bool
      - strict: bool
      - location: object
  * [`<Router>`](/packages/react-router/docs/api/Router.md)
      - history: object
      - children: node
  * [`<StaticRouter>`](/packages/react-router/docs/api/StaticRouter.md)
      - basename: string
      - location: string
      - location: object
      - context: object
      - children: node
  * [`<Switch>`](/packages/react-router/docs/api/Switch.md)
      - Switch props
  * [`history`](/packages/react-router/docs/api/history.md)
      - history is mutable
  * [`location`](/packages/react-router/docs/api/location.md)
  * [`match`](/packages/react-router/docs/api/match.md)
  * [`matchPath`](/packages/react-router/docs/api/matchPath.md)
      - pathname
      - props
  * [`withRouter`](/packages/react-router/docs/api/withRouter.md)
      - Component.WrappedComponent
      - wrappedComponentRef: func
