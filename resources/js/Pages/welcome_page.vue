<template>
    <div class="h-screen flex flex-col">
        <div class="navbar bg-base-100">
            <div class="flex-1">
                <a class="btn btn-ghost normal-case text-xl">daisyUI</a>
            </div>
            <div class="flex-none">
                <ul class="menu menu-horizontal px-1">
                    <li><a>Link</a></li>
                    <li>
                        <details>
                            <summary>Parent</summary>
                            <ul class="p-2 bg-base-100">
                                <li><a>Link 1</a></li>
                                <li><a>Link 2</a></li>
                            </ul>
                        </details>
                    </li>
                </ul>
            </div>
        </div>
        <div class="flex justify-center items-center h-full bg-base-200">
            <button class="btn btn-primary">welcome</button>
        </div>  
    </div>
</template>
<script lang="ts" setup></script>
<style></style>
