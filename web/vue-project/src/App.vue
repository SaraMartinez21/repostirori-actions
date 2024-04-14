<template>
  <div id="app">
    <table>
      <tr>
        <td @click="console.log(1)">1</td>
        <td @click="console.log(2)">2</td>
        <td @click="console.log(3)">3</td>
      </tr>
      <tr>
        <td @click="console.log(4)">4</td>
        <td @click="console.log(5)">5</td>
        <td @click="console.log(6)">6</td>
      </tr>
      <tr>
        <td @click="console.log(7)">7</td>
        <td @click="console.log(8)">8</td>
        <td @click="console.log(9)">9</td>
      </tr>
    </table>
  </div>
</template>