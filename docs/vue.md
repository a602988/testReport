# Vue demo

<ul>
  <li v-for="i in 3">{{ i }}</li>
</ul>


# Vue demo2

<div id="main">hello {{ msg }}</div>




<script>
  new Vue({
    el: '#main',
    data: { msg: 'Vue' }
  })
</script>

# Vue demo3

<vuep template="#example"></vuep>

<script v-pre type="text/x-template" id="example">
  <template>
    <div>Hello, {{ name }}!</div>
  </template>

  <script>
    module.exports = {
      data: function () {
        return { name: 'Vue' }
      }
    }
  </script>
</script>