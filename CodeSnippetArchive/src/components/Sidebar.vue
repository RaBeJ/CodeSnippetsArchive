<script setup>

</script>
<template>
    <div class="sidenav">
        <h1>CodeSnippet Archive</h1>
        <nav>
            <RouterLink to="/">Home</RouterLink><br/>
            <RouterLink to="/csharp">C#</RouterLink><br/>
            <RouterLink to="/csharp">CSharp</RouterLink><br/>
        </nav>
    </div>
</template>
<style scoped>
.sidenav h1 {
    font-size: 26px;
    color: #fe6c90;
    overflow-wrap: normal;
    padding-left: 10px;
}

/* The sidebar menu */
.sidenav {
  height: 100%; /* Full-height: remove this if you want "auto" height */
  width: 160px; /* Set the width of the sidebar */
  position: fixed; /* Fixed Sidebar (stay in place on scroll) */
  z-index: 1; /* Stay on top */
  top: 0; /* Stay at the top */
  left: 0;
  background-color: #260d34; /* Black */
  overflow-x: hidden; /* Disable horizontal scroll */
  padding-top: 10px;
}

/* The navigation menu links */
.sidenav nav {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 25px;
  color: #818181;
  display: block;
  text-align: left;
}

/* When you mouse over the navigation links, change their color */
/* .sidenav h1:hover {
  color: #fe6c90;
  background-color: #452459;
} */

/* Style page content */
.main {
  margin-left: 160px; /* Same as the width of the sidebar */
  padding: 0px 10px;
}

/* On smaller screens, where height is less than 450px, change the style of the sidebar (less padding and a smaller font size) */
@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav h1 { font-size: 12px;}
}
@media screen and (min-width: 1000px) {
  .sidenav h1 { font-size: 22px;}
}
</style>