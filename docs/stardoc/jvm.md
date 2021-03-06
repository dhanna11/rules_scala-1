<a name="#<unknown name>"></a>
## <unknown name>

<pre>
<unknown name>(name, direct, provider, used)
</pre>



### Attributes

<table class="params-table">
  <colgroup>
    <col class="col-param" />
    <col class="col-description" />
  </colgroup>
  <tbody>
    <tr id="#<unknown name>_name">
      <td><code>name</code></td>
      <td>
        String; required
        <p>
          A unique name for this target.
        </p>
      </td>
    </tr>
    <tr id="#<unknown name>_direct">
      <td><code>direct</code></td>
      <td>
        String; optional
      </td>
    </tr>
    <tr id="#<unknown name>_provider">
      <td><code>provider</code></td>
      <td>
        Label; required
      </td>
    </tr>
    <tr id="#<unknown name>_used">
      <td><code>used</code></td>
      <td>
        String; optional
      </td>
    </tr>
  </tbody>
</table>


<a name="#<unknown name>"></a>
## <unknown name>

<pre>
<unknown name>(name, compiler_classpath, global_plugins, runtime_classpath, version)
</pre>

Creates a `ScalaConfiguration`.

### Attributes

<table class="params-table">
  <colgroup>
    <col class="col-param" />
    <col class="col-description" />
  </colgroup>
  <tbody>
    <tr id="#<unknown name>_name">
      <td><code>name</code></td>
      <td>
        String; required
        <p>
          A unique name for this target.
        </p>
      </td>
    </tr>
    <tr id="#<unknown name>_compiler_classpath">
      <td><code>compiler_classpath</code></td>
      <td>
        List of labels; required
      </td>
    </tr>
    <tr id="#<unknown name>_global_plugins">
      <td><code>global_plugins</code></td>
      <td>
        List of labels; optional
        <p>
          Scalac plugins that will always be enabled.
        </p>
      </td>
    </tr>
    <tr id="#<unknown name>_runtime_classpath">
      <td><code>runtime_classpath</code></td>
      <td>
        List of labels; required
      </td>
    </tr>
    <tr id="#<unknown name>_version">
      <td><code>version</code></td>
      <td>
        String; required
      </td>
    </tr>
  </tbody>
</table>


<a name="#<unknown name>"></a>
## <unknown name>

<pre>
<unknown name>(name, configurations)
</pre>



### Attributes

<table class="params-table">
  <colgroup>
    <col class="col-param" />
    <col class="col-description" />
  </colgroup>
  <tbody>
    <tr id="#<unknown name>_name">
      <td><code>name</code></td>
      <td>
        String; required
        <p>
          A unique name for this target.
        </p>
      </td>
    </tr>
    <tr id="#<unknown name>_configurations">
      <td><code>configurations</code></td>
      <td>
        List of labels; required
      </td>
    </tr>
  </tbody>
</table>


<a name="#<unknown name>"></a>
## <unknown name>

<pre>
<unknown name>(name, compiler_bridge)
</pre>

Creates a `ZincConfiguration`.

### Attributes

<table class="params-table">
  <colgroup>
    <col class="col-param" />
    <col class="col-description" />
  </colgroup>
  <tbody>
    <tr id="#<unknown name>_name">
      <td><code>name</code></td>
      <td>
        String; required
        <p>
          A unique name for this target.
        </p>
      </td>
    </tr>
    <tr id="#<unknown name>_compiler_bridge">
      <td><code>compiler_bridge</code></td>
      <td>
        Label; required
      </td>
    </tr>
  </tbody>
</table>


