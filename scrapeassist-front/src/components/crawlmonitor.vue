<template>
  <div id="crawler-page">
    <h2 class="ui icon header">
      <i class="cogs icon"></i>
      <div class="content">
        Current Crawl Requests
        <div class="sub header">Faculty Name in University Name</div>
      </div>
    </h2>
    <table class="ui very basic collapsing celled table">
      <thead>
        <tr>
          <th>University & Faculty</th>
          <th>Date & Time Submitted</th>
          <th>Date & Time Completed</th>
          <th>Status</th>
          <th>Results</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>
            <h4 class="ui image header">
              <div class="content">
                University College London
                <div class="sub header">Faculty of Computing</div>
            </div>
          </h4></td>
          <td>
            23/9/2017 1:13pm
          </td>
          <td>
          </td>
          <td>
            Pending
          </td>
          <td>
            <!-- <button class="ui right labeled icon button">
              <i class="right arrow icon"></i>
              View Results
            </button> -->
          </td>
        </tr>
        <tr>
          <td>
            <h4 class="ui image header">
              <div class="content">
                Nanyang Technological University
                <div class="sub header">Faculty of Science</div>
            </div>
          </h4></td>
          <td>
            23/9/2017 1:13pm
          </td>
          <td>
            24/9/2017 4:28pm
          </td>
          <td>
            Completed
          </td>
          <td>
            <button class="ui right labeled icon button green">
              <i class="right arrow icon"></i>
              View Results
            </button>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
#crawler-page {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>
