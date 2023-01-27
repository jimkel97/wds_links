<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Super Useful</h3>
    <ul>
      <!-- <li><a href="xxxxx" rel="noopener">xxxxx</a></li> -->
      <li><a href="https://develop.flvs.net/collaborate/develop/coursebuilderdocs/index.htm#/" rel="noopener">Course Builder Docs</a></li>
      <li><a href="https://flvsprd.service-now.com/navpage.do" rel="noopener">ServiceNow</a></li>
      <li><a href="https://dev.azure.com/flvs/cs/_git/" rel="noopener">Azure Dev Ops</a></li>
      <li><a href="https://tinypng.com/" rel="noopener">TinyPNG</a></li>
      <li><a href="https://bamboo.flvs.net:8443/currentActivity.action" rel="noopener">Bamboo</a></li>
      <li><a href="https://develop.flvs.net/collaborate/Course/resourse_site2/index.html" rel="noopener">Resource Center</a></li>
      <li><a href="http://develop.flvs.net/Collaborate/Course/framework/4.0-presentation/index.htm" rel="noopener">FW4.0 Cheatsheet</a></li>
    </ul>
    <h3>Sometimes Useful</h3>
    <ul>
      <li><a href="https://educatortools.flvs.net/educator_tools/index.html" rel="noopener">Master Manager</a></li>
      <li><a href="http://www.mergely.com/editor?wl=1" rel="noopener">Text Compare</a></li>
      <li><a href="https://www.freeformatter.com/html-formatter.html#ad-output" rel="noopener">HTML Formatter</a></li>
      <li><a href="https://support.educator.flvs.net/educator_support_tools/" rel="noopener">LTI Manager and Alignment Tool</a></li>
      <li><a href="https://ice.flvsgl.com/wp-admin" rel="noopener">ICE WP</a></li>
    </ul>
    <h3>Company Links</h3>
    <ul>
      <li><a href="https://www.myworkday.com/flvs/d/home.htmld" rel="noopener">Workday</a></li>
    </ul>
    <h3>The Rest&hellip;</h3>
    <ul>
      <li><a href="https://www.htmlsymbols.xyz/" rel="noopener">HTML Symbols</a></li>
      <li><a href="https://develop.flvs.net/Collaborate/sdonica/master_manager/new_course/new_course.htm" rel="noopener">Create new course in MM</a></li>
      <li><a href="https://getwaves.io/" rel="noopener">SVG wave generator</a></li>
      <li><a href="https://shadows.brumm.af/" rel="noopener">Smooth shadows</a></li>
      <li><a href="https://bennettfeely.com/clippy/" rel="noopener">CSS clip-path maker</a></li>
      <li><a href="https://9elements.github.io/fancy-border-radius/" rel="noopener">Fancy Border Radius</a></li>
      <li><a href="https://type-scale.com/" rel="noopener">Visual type scale</a></li>
      <li><a href="https://animista.net/" rel="noopener">CSS animation generator</a></li>
      <li><a href="https://www.smashingmagazine.com/2021/09/interactive-learning-tools-front-end-developers" rel="noopener">Interactive Learning Tools</a></li>
      <li><a href="http://blog.froont.com/positioning-in-web-design/?utm_content=bufferc872f&utm_medium=social&utm_source=plus.google.com&utm_campaign=buffer" rel="noopener">CSS Positioning Explained</a></li>
      <li><a href="https://gridbyexample.com/" rel="noopener">Grid by Example</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
