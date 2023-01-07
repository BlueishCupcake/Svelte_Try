<script lang="ts">

  let hello = `
╭╮╱╭╮╱╱╭╮╭╮╱╱╱╭━━━╮╱╱╱╱╱╱╱╱╱╱╱╱╱╱╭━━━╮╱╱╭╮
┃┃╱┃┃╱╱┃┃┃┃╱╱╱┃╭━╮┃╱╱╱╱╱╱╱╱╱╱╱╱╱╱┃╭━╮┃╱╭╯╰╮
┃╰━╯┣━━┫┃┃┃╭━━┫┃╱╰╋╮╭┳━┳┳━━┳╮╭┳━━┫┃╱╰╋━┻╮╭╯
┃╭━╮┃┃━┫┃┃┃┃╭╮┃┃╱╭┫┃┃┃╭╋┫╭╮┃┃┃┃━━┫┃╱╭┫╭╮┃┃
┃┃╱┃┃┃━┫╰┫╰┫╰╯┃╰━╯┃╰╯┃┃┃┃╰╯┃╰╯┣━━┃╰━╯┃╭╮┃╰╮
╰╯╱╰┻━━┻━┻━┻━━┻━━━┻━━┻╯╰┻━━┻━━┻━━┻━━━┻╯╰┻━╯`

  console.log(hello)

  const handleClick = () => {
    console.log('test')
  }
</script>

<main>

  <section class="main-section">

    <h1>Hello World!</h1>
  </section>
</main>

<style>

  .main-section {
    display: flex;
    justify-content: center;
    place-content: center;
   }
</style>