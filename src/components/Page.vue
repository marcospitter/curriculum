<template>
    <div>
        <div class="row bg-secondary p-3">
            <div class="col-md-6">
                <div class="p-2 text-light">
                    <h1>Marcos Pitter, <span>Curriculum Vitae</span></h1>
                    <span>Front-End web developer - Trainee.</span><br>
                    <span>Argentino, 24 años.</span>
                    <h4 class="mt-3">Contacto:</h4>
                    <ul>
                        <li>
                            <img src="@/assets/phone.svg"/> <a href="https://wa.link/761dsq" target="_blank">3442-470229</a>
                        </li>
                        <li>
                            <img src="@/assets/envelope.svg"/> <a href="https://mail.google.com/mail/?view=cm&fs=1&tf=1&to=mpitter96.com" target="_blank">mpitter96@gmail.com</a>
                        </li>
                        <li>
                            <img src="@/assets/globe2.svg"/> <a href="https://www.linkedin.com/in/marcos-pitter-866268206/" target="_blank">LinkedIn</a>
                        </li>
                        <li>
                            <img src="@/assets/instagram.svg"/> <a href="https://www.instagram.com/marquitospitter/" target="_blank">Marcos Pitter</a>
                        </li>
                        <li>
                            <img src="@/assets/geo-alt.svg"/> <a href="https://www.google.com/maps/d/viewer?hl=es&ie=UTF8&t=h&msa=0&ll=-32.48453489999997%2C-58.2321416&spn=0.06951%2C0.109863&z=14&source=embed&mid=1r9XduDus4sKV6Eo_WNDDPeJLOz8" target="_blank">Concepción del Uruguay</a>
                        </li>
                    </ul>
                </div>
            </div>    
            <div class="col-md-6 text-center">
                <img src="https://placekitten.com/300/300" alt="Marcos Pitter"/>
            </div>
        </div>
        <br>
        <div>
            <h3 class="text-secondary">Acerca de mí</h3>
                <p class="px-4 text-justify">Soy de Herrera, Entre Ríos. En 2015 comencé la carrera de Profesorado de Inglés en UADER, teniendo como objetivo capacitarme en el idioma extranjero. El hecho de ser bilingüe me abrió las puertas a múltiples plataformas de documentacion, cursos y desafíos de desarrollo web, tanto en español como en Inglés. Mi objetivo, desde entonces, ha sido crecer como profesional en un ambiente donde pueda aplicar y, por supuesto, seguir adquiriendo nuevos conocimientos de desarrollo web front-end. Me presento como una persona cordial y servicial, con mucha autodeterminación y con experiencia laboral con equipos de trabajo en conjunto. Creo firmemente en el aprendizaje autodidacta y es por esto que me creo capaz de encarar nuevos desafíos.</p>
        </div>
        <br>
        <div>
            <h3 class="text-secondary">Habilidades</h3>
            <ul>
                <li>Nivel de inglés: alto. (Estudiante avanzado del profesorado de Inglés. 2015-actualidad).</li>
                <li>Conocimiento de estructura HTML</li>
                <li>conocimiento de estilos CSS.</li>
                <li>Conocimiento básico de Javascript.</li>
                <li>Manejo básico de Vue CLI, Vuetify y librería de estilos de Bootstrap.</li>
                <li>Manejo de Visual Studio code.</li>
                <li>conocimiento sobre control de versiones con GIT</li>
                <li>experiencia en mantenimiento, actualización y reparación de computadoras, tanto hardware como software.</li>
                
            </ul>
        </div>
        <br>
        <div>
            <h3 class="text-secondary ">Certificaciones</h3>
            <ul>
                <li><a class="certificados" href="https://www.udemy.com/certificate/UC-cf6c8358-aec6-48f2-876d-1910bc6685ab/" target="_blank">APLICACIONES WEB DESDE 0</a>, por Wilber José Matus Gonzalez - UDEMY.</li>
                <li><a class="certificados" href="https://www.udemy.com/certificate/UC-9ddfbad0-d512-4ac4-8503-dde742d33648/" target="_blank">Front End Web Development Ultimate Course 2021</a>, por Learn Tech Plus - UDEMY.</li>
                <li><a class="certificados" href="https://codigofacilito.com/user_quizzes/475747.pdf" target="_blank">CURSO PROFESIONAL DE JAVASCRIPT</a>, por Uriel Hernandez- Código Facilito.</li>
                <li><a class="certificados" href="https://www.udemy.com/certificate/UC-15868b43-065b-45ba-8b14-140cb689a63a/" target="_blank">Git and GitHub Projects: Project Based Learning (8 Projects)</a>, por Learnkart Technology Pvt Ltd - UDEMY.</li>

            </ul>
        </div>
        <br>
        <div>
            <h3 class="text-secondary">Experiencia Laboral</h3>
            <ul>
                <li>Atención al cliente. Período: mayo 2019 – febrero 2020 (inicio aislamiento social, preventivo y obligatorio) febrero 2021- actualidad</li>
            </ul>
        </div>
        <br>
        <br>
    </div>
</template>

<script>
    export default {
        name: 'Page'
    }
</script>

<style>
    body, html{
        background-color: rgb(228, 228, 228);
        
    }

    a{
        color: white;
        text-decoration:none;
    }

    a.certificados{
        color: black;
    }

    span{
        font-weight: lighter;
    }
</style>
