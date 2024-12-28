<template>
<div class="footer">
    <div>
        <h3>Hubungi Kami</h3>
        <p>SMKN 4 Tasikmalaya<br>
        Jl. Depok Kel. Sukamenak Kec. Purbaratu<br>
        Kota Tasikmalaya 46196.</p>
        <p>📞 +62265312059</p>
        <p>✉️ <a href="mailto:info@smkn4-tsm.sch.id">info@smkn4-tsm.sch.id</a></p>
    </div>
    <div>
        <h3>Media Sosial</h3>
        <ul>
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">Instagram</a></li>
        </ul>
    </div>
    <div>
        <h3>Link Eksternal</h3>
        <ul>
            <li><a href="#">Kemdikbud</a></li>
            <li><a href="#">Dapodikdasmen</a></li>
            <li><a href="#">PSMK</a></li>
            <li><a href="#">Disdik Jabar</a></li>
        </ul>
    </div>
</div>
</template>

<style scoped>
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

.footer {
    background-color: #333;
    color: #fff;
    display: flex;
    justify-content: space-between;
    padding: 20px;
    font-size: 14px;
}

.footer div {
    flex: 1;
}

.footer div:not(:last-child) {
    margin-right: 20px;
}

.footer h3 {
    margin: 0 0 10px 0;
    font-size: 16px;
}

.footer ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

.footer ul li {
    margin: 5px 0;
}

.footer a {
    color: #fff;
    text-decoration: none;
}

.footer a:hover {
    text-decoration: underline;
}
</style>