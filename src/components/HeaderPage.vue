<template>
    <div class="container">
        <font-awesome-icon class="menu-icon" icon="fa-solid fa-bars" size="lg" :style="{ color: 'blue' }" />
        <div class="header-container">
            <div>
                <div class="logo wr">
                    <a href="https://water.rajasthan.gov.in/wr/#/home/dptHome"><img src="../assets/Water-Resources.png"
                            alt="Water Resources Logo" class="img">
                    </a>
                </div>
            </div>

            <div class="mid-nav-conatainer">
                <div class="tagline">
                    <p>Rajasthan Water Resources information System</p>
                </div>

                <div class="nav headcenter numfont ">
                    <router-link to="/" class="btn-t numfont">Home</router-link>
                    <router-link to="/aboutus" class="btn-t numfont">About RWRIS</router-link>

                    <div class="dropdown dropdownmargin">
                        <button class="dropbtn numfont">Services</button>
                        <div class="dropdown-content numfont">
                            <router-link to="/canal">Canal Data Analysis</router-link>
                            <router-link to="/rainfallRain">Rainfall Data Analysis</router-link>
                            <router-link to="/dam">Dam Data Analysis</router-link>
                            <router-link to="/rtdas">RT-DAS</router-link>
                            <!-- <router-link to="/wims">WIMS</router-link> -->
                            <router-link to="/scada">Scada Analysis</router-link>
                            <router-link to="/historical">Historical Data</router-link>
                            <router-link to="/groundwater">Groundwater Data</router-link>
                        </div>
                    </div>
                    <router-link to="/geoportal" class="btn-t numfont">Geo-Portal</router-link>
                    <div class="dropdown dropdownmargin">
                        <button class="dropbtn numfont">Links</button>
                        <div class="dropdown-content numfont">
                            <a href="https://bhuvan-wbis.nrsc.gov.in/?id=212900679349068962" target="_blank">Water
                                Bodies
                                Information System (WBIS)</a>
                            <a href="https://water.rajasthan.gov.in/wr/#/home/dptHome" target="_blank">Department of
                                Water
                                Resource (WRD)</a>
                            <a href="https://ffs.india-water.gov.in/#/" target="_blank">Central Water Commission
                                (CWC)</a>
                        </div>
                    </div>
                    <router-link to="/contactus" class="btn-t numfont">Contact Us</router-link>
                </div>
            </div>

            <div>
                <div class="logo nhp">
                    <a href="https://nhp.mowr.gov.in/"> <img src="../assets/nph-logo.png"
                            alt="National Hydeology Project Logo" class="img">
                    </a>
                </div>
            </div>
        </div>

        <font-awesome-icon class="user-icon" icon="fa-solid fa-user" size="lg" :style="{ color: 'blue' }" />
    </div>

</template>

<script>
export default {
    name: 'HeaderPage',
}
</script>

<style></style>