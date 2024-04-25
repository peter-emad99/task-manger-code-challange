<script setup lang="ts">
const taskStore = useTaskStore()
</script>

<template>
  <div class="container">
    <h1 class="text-red-600 text-xl font-bold text-center">Task Manager</h1>
    <main class="grid grid-cols-[1fr,4fr] gap-4 p-4">
      <Card>
        <CardHeader>
          <CardTitle>active time tracking</CardTitle>
          <CardDescription>list of tasks with active time tracking</CardDescription>
        </CardHeader>
        <CardContent> Card Content </CardContent>
        <CardFooter> Card Footer </CardFooter>
      </Card>
      <Card>
        <CardHeader>
          <CardTitle>tasks list</CardTitle>
          <CardDescription>list of tasks </CardDescription>
        </CardHeader>
        <CardContent> Card Content </CardContent>
        <CardFooter> Card Footer </CardFooter>
      </Card>
    </main>
  </div>
</template>

<style scoped></style>
