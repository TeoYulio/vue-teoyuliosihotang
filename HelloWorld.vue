<template>
  <div class="hello" >
    <h1>{{ msg }}</h1>
    <p>
      Informatics Engineering Student | Amateur Graphic Design and Photography<br>
      More Portfolio
      <a href="https://teoyulio.000webhostapp.com" target="_blank" rel="noopener">Teo Yulio Sihotang</a>
    </p>
    <h3>Studies</h3>
   
    <ul>
    <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/506fb595-2bf5-e011-af47-058e0bc9996b" target="_blank" rel="noopener">SD Xaverius Emmanuel Tanjung Enim</a></li>
    <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/00883096-2BF5-E011-9F4F-F146978A5380" target="_blank" rel="noopener">SMP Xaverius Emmanuel Tanjung Enim</a></li>
      <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/435d1905-3d72-43ae-bfa1-bc19943fa0ee" target="_blank" rel="noopener">SMAN 3 Muara Enim</a></li>
      <li><a href="https://mdp.ac.id/" target="_blank" rel="noopener">Universitas MDP Palembang</a></li>
    </ul>
    <h3>Photography</h3>
    <ul>
      <li><a href="https://www.instagram.com/p/CUrS5QGBcOD/?utm_source=ig_web_copy_link" target="_blank" rel="noopener">Instagram @teojuliosht</a></li>
    </ul>
    <h3>Coming soon project</h3>
    <ul>
      <li><a href="https://www.instagram.com/lazycorner.id" target="_blank" rel="noopener">Lazy Corner</a></li>
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
  margin:0;
}
ul {
  list-style-type:;
  padding:20px;

}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
