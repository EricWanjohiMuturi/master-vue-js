<script setup>

</script>

<template>
    <div class="form">
        <div class="add-task">
          <h3>Add a new task</h3>
          <label for="title">Title *</label>
          <input type="text" name="title" placeholder="Enter a title..."><br />
          <textarea name="description" rows="4" placeholder="Enter a description..." /><br />
          <label for="description">Description*</label>
          <button @click="addTask" class="btn gray">Add Task</button>
        </div>
    </div>
</template>