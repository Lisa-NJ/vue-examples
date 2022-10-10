 <template>
  <div class="demo">
    <h2>school name: {{ name }}</h2>
    <h2>school address: {{ address }}</h2>
  </div>
</template>
 
<script>
export default {
  name: "School",
  data() {
    return {
      name: "atGuigu",
      address: "Beijing",
    };
  },
};
</script>

<style>
.demo {
  background-color: orange;
}
</style>