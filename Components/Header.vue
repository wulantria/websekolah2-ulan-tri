    <template>
    <nav class="navbar navbar-expand-lg bg-success">
        <div class="container">
            <img src="/assets/img/Logo-Smk.png" alt="logo smk" width="100px" height="100px">
            <a class="navbar-brand" href="#">SMK</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <NuxtLink class="nav-link" :class="{ active: route.name == 'Contack' }" to="/Contack">Contack</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink class="nav-link" :class="{ active: route.name == 'Fasilitas' }" to="/Fasilitas">Fasilitas</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink class="nav-link" :class="{ active: route.name == 'Jurusan' }" to="/Jurusan">Jurusan</NuxtLink>
                    </li>
                    <li class="nav-item">
                        <NuxtLink class="nav-link" :class="{ active: route.name == 'Profil Sekolah' }" to="/Profil Sekolah">Profil Sekolah</NuxtLink>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    </template>

    <script setup>
    const route = useRoute()

    console.log(route.name)
    </script>