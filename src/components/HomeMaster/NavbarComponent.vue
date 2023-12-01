<template>
    <!-- Topbar Start -->
    <div class="container-fluid bg-dark py-2 d-none d-md-flex position-fixed">
        <div class="container">
            <div class="d-flex justify-content-between topbar">
                <div class="top-info">
                    <small class="me-3 text-white-50"><a href="#"><i
                                class="fas fa-map-marker-alt me-2 text-secondary"></i></a>00100 Nairobi, Kenya</small>
                    <small class="me-3 text-white-50"><a href="#"><i
                                class="fas fa-envelope me-2 text-secondary"></i></a>savycodesolutions@gmail.com</small>
                </div>
                <div id="note" class="text-white d-none d-xl-flex"><small>Welcome to Savycode Solutions Limited</small></div>
                <div class="top-link">
                    <a href="" class="bg-light nav-fill btn btn-sm-square rounded-circle"><i
                            class="fab fa-facebook-f text-primary"></i></a>
                    <a href="" class="bg-light nav-fill btn btn-sm-square rounded-circle"><i
                            class="fab fa-twitter text-primary"></i></a>
                    <a href="" class="bg-light nav-fill btn btn-sm-square rounded-circle"><i
                            class="fab fa-instagram text-primary"></i></a>
                    <a href="" class="bg-light nav-fill btn btn-sm-square rounded-circle me-0"><i
                            class="fab fa-linkedin-in text-primary"></i></a>
                </div>
            </div>
        </div>
    </div>
    <!-- Topbar End -->

    <!-- Navbar Start -->
    <div class="container-fluid bg-success position-fixed mt-5">
        <div class="container">
            <nav class="navbar navbar-dark navbar-expand-lg py-0">
                <a href="index.html" class="navbar-brand">
                    <!-- <a href="index.html" class="logo me-auto"><img src="../../assets/img/Savy (1).png" alt="" class="img-fluid"></a> -->
                    <h3 class="text-white fw-bold d-block">Savy<span class="text-primary">Code</span> </h3>
                </a>
                <button type="button" class="navbar-toggler me-0" data-bs-toggle="collapse"
                    data-bs-target="#navbarCollapse">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse bg-transparent" id="navbarCollapse">
                    <div class="navbar-nav ms-auto mx-xl-auto p-0">
                        <router-link to="/" class="nav-item nav-link active text-secondary">Home</router-link>
                        <router-link to="/about" class="nav-item nav-link">About</router-link>
                        <div class="nav-item dropdown">
                            <router-link to="/service" class="nav-link dropdown-toggle" data-bs-toggle="dropdown">Services</router-link>
                            <div class="dropdown-menu rounded">
                                <a>
                                    <router-link to="/agency" class="dropdown-item">Agency</router-link>
                                </a>
                                <a href="team.html" class="dropdown-item">Systems & Solutions</a>
                            </div>
                        </div>
                        <a href="project.html" class="nav-item nav-link">Projects</a>
                        <div class="nav-item dropdown">
                            <a href="#" class="nav-link dropdown-toggle" data-bs-toggle="dropdown">Pages</a>
                            <div class="dropdown-menu rounded">
                                <a href="blog.html" class="dropdown-item">Our Blog</a>
                                <a href="team.html" class="dropdown-item">Our Team</a>
                                <a href="testimonial.html" class="dropdown-item">Testimonial</a>
                                <a href="404.html" class="dropdown-item">404 Page</a>
                            </div>
                        </div>
                        <router-link to="/contact" class="nav-item nav-link">Contact</router-link>
                    </div>
                </div>
                <div class="d-none d-xl-flex flex-shirink-0">
                    <div id="phone-tada" class="d-flex align-items-center justify-content-center me-4">
                        <a href="" class="position-relative">
                            <i class="fa fa-phone-alt text-white fa-2x"></i>
                            <div class="position-absolute" style="top: -7px; left: 20px;">
                                <span><i class="fa fa-comment-dots text-secondary"></i></span>
                            </div>
                        </a>
                    </div>
                    <div class="d-flex flex-column pe-4 border-end">
                        <span class="text-white-50">Have any questions?</span>
                        <span class="text-secondary">Call: +254 700458981</span>
                    </div>
                </div>
            </nav>
        </div>
    </div><!-- Navbar End -->
</template>

<script>
export default {

}
</script>

<style></style>