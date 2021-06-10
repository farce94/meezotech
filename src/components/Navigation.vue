<template>
    <ul class="main-menu nav justify-content-center">
        <li>
            <router-link to="/">Home</router-link>
        </li>
        <li>
            <router-link to="/about">About</router-link>
        </li>
        <!-- <li class="has-submenu">
            <n-link to="/service">Service</n-link>
            <ul class="submenu-nav">
                <li>
                    <n-link to="/service">Service</n-link>
                </li>
                <li>
                    <n-link to="/service-details">Service Details</n-link>
                </li>
            </ul>
        </li> -->
        <li class="has-submenu">
            <router-link to="/project">Project</router-link>
            <!-- <ul class="submenu-nav">
                <li>
                    <n-link to="/project">Project</n-link>
                </li>
                <li>
                    <n-link to="/project-details">Project Details</n-link>
                </li>
            </ul> -->
        </li>
        <!-- <li class="has-submenu">
            <n-link to="/blog">Blog</n-link>
            <ul class="submenu-nav">
                <li>
                    <n-link to="/blog">Blog</n-link>
                </li>
                <li>
                    <n-link to="/blog-details">Blog Details</n-link>
                </li>
            </ul>
        </li> -->
        <li>
            <router-link to="/careers">Careers</router-link>
        </li>
    </ul>
</template>