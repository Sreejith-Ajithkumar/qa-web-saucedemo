# UI Test Plan — SauceDemo
Scope: login, inventory view, add-to-cart.
Browsers: Edge/Chrome (latest), headless in CI.
Entry: site reachable, test creds available. Exit: all high/critical pass, 0 open P0 bugs.
Risks: dynamic locators, flaky network.
Reporting: pytest-HTML, screenshots on failure, (later) Azure DevOps bug auto-create.
