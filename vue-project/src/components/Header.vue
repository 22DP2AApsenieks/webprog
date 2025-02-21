<script setup>

</script>


<template>
    <header>
        <h1>Fitlibrary</h1>
        <div class="hamburger" onclick="toggleDropdown()">
            <div></div>
            <div></div>
            <div></div>
        </div>
        <div class="nav-links">
            <table>
                <tr>
                    <!-- <div class="vadibas_josla">Signup</div></a> -->
                    <th><RouterLink to="/signup">Sign up</RouterLink></th>
                    <th><a href="login.html"><div class="vadibas_josla">Login</div></a></th>
                    <th><a href="index.html"><div class="vadibas_josla">Home</div></a></th>
                    <th><a href="about.html"><div class="vadibas_josla">About</div></a></th>
                    <th><a href="contact.html"><div class="vadibas_josla">Contact</div></a></th>
                    <th><a href="coaching.html"><div class="vadibas_josla">Coaching</div></a></th>
                </tr>
            </table>
        </div>    
    </header>
</template>

<style scoped>
header {
  background-color: rgb(255, 255, 255);
  border-radius: 5px;
  transition: background, 1.5s;
  width: 7rem;
  height: 1.5rem;
  color: crimson;
  text-align: center;
}
</style>