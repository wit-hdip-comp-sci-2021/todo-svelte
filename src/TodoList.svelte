<script>
  export let todoItems = [];
</script>

<div class="section box">
  <div class="title is-6">Things yet do</div>
  <table class="table is-fullwidth">
    <thead>
      <th>Task</th>
      <th>Date</th>
      <th></th>
    </thead>
    <tbody>
      {#each todoItems as todo}
        <tr>
          <td> {todo.text} </td>
          <td> {todo.date} </td>
        </tr>
      {/each}
    </tbody>
  </table>
</div>
