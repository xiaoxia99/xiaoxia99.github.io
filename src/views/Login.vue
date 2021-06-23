 <template>
  <form >
    <input type="text" />
    <input type="text" />
    <input type="submit" value="登录" />
  </form>
</template>
          
 <script>
export default {};
</script>
       
 <style scoped>
 /*
传统：一个个html写style相互不污染
但是：vue框架中 默认是相互影响
解决：scoped 即可
*/
 *{color:red}
</style>