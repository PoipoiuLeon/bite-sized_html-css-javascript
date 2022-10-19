<template>
  <form>

    Name: <input type="text" required>
    </div>
    <div>
    Age: <input type="number" required>
    </div>
    <div>
      <input type="checkbox"> is enrolled?
    </div>
    <div>
      <textarea></textarea>
    </div>
    <div>
      Color:
      <select>
        <option>red</option>
        <option>Blue</option>
        <option selected>Green</option>
      </select>
    </div>
    <div>
      Countries:
      <select multiple>
        <option>Australia</option>
        <option>Canada</option>
        <option>USA</option>
        <option>Mexico</option>
      </select>
    </div>
    <div>
    <input type="submit" value="Save">
    </div>
  </form>
</template>

<script>
export default {
  name: "Forms"
}
</script>

<style scoped>

</style>