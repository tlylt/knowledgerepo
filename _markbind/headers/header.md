<header>
  <navbar type="dark">
    <a slot="brand" href="{{baseUrl}}/index.html" title="Home" class="navbar-brand">L</a>
    <li><a href="{{baseUrl}}/contents/OpenSource.html" class="nav-link">Open Source</a></li>
    <li><a href="{{baseUrl}}/contents/CS2030S.html" class="nav-link">CS2030S</a></li>
    <li><a href="{{baseUrl}}/contents/CS1231S.html" class="nav-link">CS1231S</a></li>
    <dropdown header="Completed" class="nav-link">
      <li><a href="{{baseUrl}}/contents/CS2040.html" class="dropdown-item">CS2040</a></li>
      <li><a href="{{baseUrl}}/contents/CS1010X.html" class="dropdown-item">CS1010X</a></li>
    </dropdown>
    <li slot="right">
      <form class="navbar-form">
        <searchbar :data="searchData" placeholder="Search" :on-hit="searchCallback" menu-align-right></searchbar>
      </form>
    </li>
  </navbar>
</header>
