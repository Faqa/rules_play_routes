<a name="#play_routes"></a>
## play_routes

<pre>
play_routes(name, generate_reverse_router, include_play_imports, namespace_reverse_router, routes_generator, routes_imports, srcs)
</pre>

Compiles Play routes files templates to Scala sources files.

### Attributes

<table class="params-table">
  <colgroup>
    <col class="col-param" />
    <col class="col-description" />
  </colgroup>
  <tbody>
    <tr id="#play_routes_name">
      <td><code>name</code></td>
      <td>
        String; required
        <p>
          A unique name for this rule.
        </p>
      </td>
    </tr>
    <tr id="#play_routes_generate_reverse_router">
      <td><code>generate_reverse_router</code></td>
      <td>
        Boolean; optional
        <p>
          Whether the reverse router should be generated. Setting to false may reduce compile times if it's not needed.
        </p>
      </td>
    </tr>
    <tr id="#play_routes_include_play_imports">
      <td><code>include_play_imports</code></td>
      <td>
        Boolean; optional
        <p>
          If true, include the imports the Play project includes by default.
        </p>
      </td>
    </tr>
    <tr id="#play_routes_namespace_reverse_router">
      <td><code>namespace_reverse_router</code></td>
      <td>
        Boolean; optional
        <p>
          Whether the reverse router should be namespaced. Useful if you have many routers that use the same actions.
        </p>
      </td>
    </tr>
    <tr id="#play_routes_routes_generator">
      <td><code>routes_generator</code></td>
      <td>
        String; optional
        <p>
          The full class of the routes generator, e.g., `play.routes.compiler.InjectedRoutesGenerator`
        </p>
      </td>
    </tr>
    <tr id="#play_routes_routes_imports">
      <td><code>routes_imports</code></td>
      <td>
        List of strings; optional
        <p>
          Additional imports to import to the Play routes
        </p>
      </td>
    </tr>
    <tr id="#play_routes_srcs">
      <td><code>srcs</code></td>
      <td>
        List of labels; required
        <p>
          Play routes files
        </p>
      </td>
    </tr>
  </tbody>
</table>


