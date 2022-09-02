<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Super Useful</h3>
    <ul>
      <!-- <li><a href="xxxxx" target="_blank" rel="noopener">xxxxx</a></li> -->
      <li><a href="https://develop.flvs.net/collaborate/develop/coursebuilderdocs/index.htm#/" target="_blank" rel="noopener">Course Builder Docs</a></li>
      <li><a href="https://flvsprd.service-now.com/navpage.do" target="_blank" rel="noopener">ServiceNow</a></li>
      <li><a href="https://dev.azure.com/flvs/cs/_git/" target="_blank" rel="noopener">Azure Dev Ops</a></li>
      <li><a href="https://tinypng.com/" target="_blank" rel="noopener">TinyPNG</a></li>
      <li><a href="http://app64.fvs.fvsonline.net:8085/currentActivity.action" target="_blank" rel="noopener">Bamboo</a></li>
      <li><a href="https://develop.flvs.net/collaborate/Course/resourse_site2/index.html" target="_blank" rel="noopener">Resource Center</a></li>
      <li><a href="http://develop.flvs.net/Collaborate/Course/framework/4.0-presentation/index.htm" target="_blank" rel="noopener">FW4.0 Cheatsheet</a></li>
    </ul>
    <h3>Sometimes Useful</h3>
    <ul>
      <li><a href="https://educatortools.flvs.net/educator_tools/index.html" target="_blank" rel="noopener">Master Manager</a></li>
      <li><a href="http://www.mergely.com/editor?wl=1" target="_blank" rel="noopener">Text Compare</a></li>
      <li><a href="https://www.freeformatter.com/html-formatter.html#ad-output" target="_blank" rel="noopener">HTML Formatter</a></li>
      <li><a href="https://support.educator.flvs.net/educator_support_tools/" target="_blank" rel="noopener">LTI Manager and Alignment Tool</a></li>
      <li><a href="https://ice.flvsgl.com/wp-admin" target="_blank" rel="noopener">ICE WP</a></li>
    </ul>
    <h3>Company Links</h3>
    <ul>
      <li><a href="https://www.myworkday.com/flvs/d/home.htmld" target="_blank" rel="noopener">Workday</a></li>
    </ul>
    <h3>The Rest&hellip;</h3>
    <ul>
      <li><a href="https://www.htmlsymbols.xyz/" target="_blank" rel="noopener">HTML Symbols</a></li>
      <li><a href="https://develop.flvs.net/Collaborate/sdonica/master_manager/new_course/new_course.htm" target="_blank" rel="noopener">Create new course in MM</a></li>
      <li><a href="https://getwaves.io/" target="_blank" rel="noopener">SVG wave generator</a></li>
      <li><a href="https://shadows.brumm.af/" target="_blank" rel="noopener">Smooth shadows</a></li>
      <li><a href="https://type-scale.com/" target="_blank" rel="noopener">Visual type scale</a></li>
      <li><a href="https://animista.net/" target="_blank" rel="noopener">CSS animation generator</a></li>
      <li><a href="https://www.smashingmagazine.com/2021/09/interactive-learning-tools-front-end-developers" target="_blank" rel="noopener">Interactive Learning Tools</a></li>
      <li><a href="http://blog.froont.com/positioning-in-web-design/?utm_content=bufferc872f&utm_medium=social&utm_source=plus.google.com&utm_campaign=buffer" target="_blank" rel="noopener">CSS Positioning Explained</a></li>
      <li><a href="https://gridbyexample.com/" target="_blank" rel="noopener">Grid by Example</a></li>
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
