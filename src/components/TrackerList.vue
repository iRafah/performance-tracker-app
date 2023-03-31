<script setup>

import TrackerItem from '@/components/TrackerItem.vue'

</script>

<template>
    <div class="tracker_wrapper">
        <table>
            <tr>
                <th>ID</th>
                <th>Ticket <!-- Add Icons using String format -->
            </th>
                <th>Estimated time <font-awesome-icon icon="fa-regular fa-clock" /></th>
                <th>Closed at <font-awesome-icon icon="fa-brands fa-twitter" /></th>
                <th>Time left/passed</th>
                <th>Type</th>
            </tr>
            <tr>
                <td>#01</td>
                <td><a href="https://www.w3schools.com" target="_blank">ZT-05</a></td>
                <td>3h</td>
                <td>1h 20m</td>
                <td>1h 40m</td>
                <td>Bug</td>
            </tr>
            <tr>
                <td>#02</td>
                <td>COR-750</td>
                <td>1h</td>
                <td>1h 20m</td>
                <td>-20m</td>
                <td>Task</td>
            </tr>
            <tr>
                <td>#03</td>
                <td>ZT-06</td>
                <td>5h10m</td>
                <td>1h30m</td>
                <td>3h40m</td>
                <td>Bug</td>
            </tr>
            <tr>
                <td>#04</td>
                <td>ALZSD-15</td>
                <td>3h</td>
                <td>1h20m</td>
                <td>1h40m</td>
                <td>Bug</td>
            </tr>
            <tr>
                <!-- Load each item -->
                <TrackerItem />
            </tr>
        </table>
    </div>
</template>

<style scoped>

.tracker_wrapper {
    width: 80%;
    background: #f3f3f3;
    margin: 0 auto;
    border-radius: 5px;
    border: none;
}
.tracker_wrapper table {
  width: 100%;
  font-family: 'Open Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  border: none;
  border-collapse:collapse;
}

.tracker_wrapper table th {
    background: #565968;    
    color: #fff;
    font-size: 0.8rem;
}  

.tracker_wrapper table td, .tracker_wrapper table th {
  text-align: center;
  padding: 8px;
}

.tracker_wrapper table tr:nth-child(even) {
  background-color: #F9FAFE;
}

.tracker_wrapper table tr:nth-child(odd) {
  background-color: #fff;
}
</style>