<template>
    <section id="presentation-card" class="d-flex justify-center">
        <v-card
            rounded="xl"
            class="flex-grow-1 ma-1"
            max-width="700"
            min-width="335"
            height="400"
        >
            <v-img
                rounded="xl"
                src="/images/me_5.jpeg"
                alt="me"
                gradient="to bottom right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.7)"
                max-width="700"
                min-width="250"
                height="400"
                cover
            >
                <v-row no-gutters class="d-flex" style="height: 50%">
                    <v-col class="d-flex justify-end mr-4">
                        <v-btn
                            density="compact"
                            icon="mdi-linkedin"
                            class="mx-1 mt-4"
                            size="large"
                            color="blue"
                            href="https://www.linkedin.com/in/jorge-isla-tejo-7218a11bb/"
                            target="_blank"
                        ></v-btn>
                        <v-btn
                            density="compact"
                            icon="mdi-github"
                            class="mx-1 mt-4"
                            size="large"
                            color="grey"
                            href="https://github.com/jislat"
                            target="_blank"
                        ></v-btn>
                        <v-btn
                            density="compact"
                            icon="mdi-instagram"
                            class="mx-1 mt-4"
                            size="large"
                            color="purple"
                            href="https://www.instagram.com/george.island/"
                            target="_blank"
                        ></v-btn>
                    </v-col>
                </v-row>
                <v-row no-gutters class="d-flex" style="height: 30%">
                    <v-col class="d-flex justify-end align-end mr-3">
                        <span class="text-h3 text-white"> Jorge Isla </span>
                    </v-col>
                </v-row>
                <v-row no-gutters class="d-flex" style="height: 20%">
                    <v-col class="d-flex justify-end align-end mr-3">
                        <span
                            class="mb-7 mr-2 text-sm-h6 text-text-subtitle-1 text-white"
                        >
                            Husband
                        </span>
                        <br />
                        <span
                            class="mb-5 mr-2 text-sm-h6 text-text-subtitle-1 text-white"
                        >
                            Cat Lover
                        </span>
                        <br />
                        <span
                            class="mb-3 text-sm-h6 text-text-subtitle-1 text-white"
                        >
                            Software Engineer
                        </span>
                    </v-col>
                </v-row>
            </v-img>
        </v-card>
    </section>
    <section id="about-me" class="d-flex justify-center">
        <v-card
            rounded="xl"
            max-width="700"
            min-width="335"
            class="ma-1 pa-4"
            color="#006E89"
            style="border-color: #004863; border-width: 1px"
        >
            <v-card-title>About Me</v-card-title>
            <v-card-text>
                <span class="text-body-1">
                    I don't know how you found me here, but I'm glad you did.
                    I'm going to tell you a little bit about myself.<br />
                    First of all, I'm a husband. Yes, I'm happily married since
                    February 1, 2023.
                    <br />
                    Also, I'm a father of
                    <span class="text-decoration-line-through mr-1">1</span>
                    <span class="text-decoration-line-through">2</span>
                    3 beautiful cats. <br />I'm from Chile and currently living
                    in Santiago.
                </span>
            </v-card-text>
            <v-card-actions>
                <v-btn
                    density="compact"
                    prepend-icon="mdi-instagram"
                    size="large"
                    color="purple"
                    href="https://www.instagram.com/george.island/"
                    target="_blank"
                    class="text-none"
                    rounded="lg"
                    variant="elevated"
                    >My Instagram</v-btn
                >
            </v-card-actions>
        </v-card>
    </section>
    <section id="projects" class="d-flex flex-wrap justify-center">
        <v-card
            rounded="xl"
            min-width="335"
            max-width="700"
            class="ma-1 pa-4 flex-grow-1"
            color="#004863"
        >
            <v-card-title>Projects</v-card-title>
            <v-card-text>
                <span class="text-body-1">
                    Currently, I'm working on myself, studying a lot about
                    multiple topics, mainly investments. <br />
                    I'm also completing my master's in computer science.
                </span>
            </v-card-text>
        </v-card>
    </section>
    <section
        id="professional-experience"
        class="d-flex flex-wrap justify-center"
    >
        <v-card
            rounded="xl"
            min-width="335"
            max-width="700"
            class="ma-1 pa-4 flex-grow-1"
            color="#006E89"
            style="border-color: #004863; border-width: 1px"
        >
            <v-card-title>Professional Experience</v-card-title>
            <v-card-text class="text-body-1">
                <span
                    >My professional experience primarily involves executing
                    projects, with a focus on my role as a software
                    engineer.</span
                ><br /><span>
                    I have worked extensively with technologies such as Python
                    and Vue, utilizing frameworks like Django Rest Framework and
                    Nuxt3.</span
                >
            </v-card-text>
            <v-card-actions>
                <v-btn
                    class="text-none"
                    rounded="lg"
                    variant="elevated"
                    href="https://jislawebpagebucket.s3.amazonaws.com/resumeJorgeIsla.pdf"
                    target="_blank"
                    prepend-icon="mdi-file-account"
                    color="#079CA3"
                    >My Resume</v-btn
                >
            </v-card-actions>
        </v-card>
    </section>
    <section id="contact-me" class="d-flex flex-wrap justify-center">
        <v-card
            rounded="xl"
            min-width="335"
            max-width="700"
            class="ma-1 pa-4 flex-grow-1"
            color="#004863"
        >
            <v-card-title>Contact Me</v-card-title>
            <v-card-text>
                <span class="text-body-1"
                    >If you’d like to get in touch, feel free to email me at
                    coke.isla@gmail.com or send me a message on LinkedIn.</span
                >
            </v-card-text>
            <v-card-actions>
                <v-btn
                    prepend-icon="mdi-linkedin"
                    color="blue"
                    class="text-none"
                    rounded="lg"
                    variant="elevated"
                >
                    My Linkedin</v-btn
                >
                <v-btn
                    prepend-icon="mdi-email"
                    class="text-none"
                    rounded="lg"
                    variant="elevated"
                    color="#079CA3"
                    >Email</v-btn
                >
            </v-card-actions>
        </v-card>
    </section>
</template>
<script setup lang="ts"></script>
