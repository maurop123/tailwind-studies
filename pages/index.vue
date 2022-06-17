<template>
    <div class="container mx-auto flex flex-wrap h-screen place-content-center grid grid-cols-1">
        <div class="mx-auto">
            <img src="~/assets/github-profile-pic.jpeg"
                class="w-36 h-36 rounded-full drop-shadow-md mb-5"
            />
        </div>
        <h1 class="mx-auto mb-7 text-5xl hover:text-sky-400/100">
            <font-awesome-icon :icon="['fab', 'github']" />
            <a href="https://github.com/maurop123"
              class="font-sans hover:italic underline hover:no-underline"
            >
                maurop123
            </a>
        </h1>
        <h2 class="mx-auto mb-5 text-4xl hover:text-sky-400/100">
            <font-awesome-icon :icon="['fab', 'linkedin']" />
            <a href="https://www.linkedin.com/in/mauro-perez-25634111/"
              class="font-sans hover:italic underline hover:no-underline"
            >
                Mauro Perez
            </a>
        </h2>
    </div>
</template>