<template>
    <div
        class="offcanvas offcanvas-start"
        data-bs-scroll="true"
        data-bs-backdrop="false"
        tabindex="-1"
        id="offcanvasScrolling"
        aria-labelledby="offcanvasScrollingLabel"
    >
        <div class="offcanvas-header bg-dark">
            <h5 class="offcanvas-title text-light" id="offcanvasExampleLabel">
                ADMINISTRACIJA
            </h5>
            <button
                type="button"
                class="btn-close"
                data-bs-dismiss="offcanvas"
                aria-label="Close"
            ></button>
        </div>
        <div class="offcanvas-body modalBody">
            <div class="list-group w-100">
                <div class="d-flex align-items-center">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="25"
                        height="25"
                        fill="currentColor"
                        class="bi bi-people text-light"
                        viewBox="0 0 16 16"
                    >
                        <path
                            d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1zm-7.978-1L7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002-.014.002zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4m3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0M6.936 9.28a6 6 0 0 0-1.23-.247A7 7 0 0 0 5 9c-4 0-5 3-5 4q0 1 1 1h4.216A2.24 2.24 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816M4.92 10A5.5 5.5 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275ZM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0m3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4"
                        />
                    </svg>

                    <router-link
                        class="list-group-item list-group-item-action text-light"
                        to="/users"
                        >Korisnici</router-link
                    >
                </div>
                <div class="d-flex align-items-center">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="25"
                        height="25"
                        fill="currentColor"
                        class="bi bi-person-badge-fill text-light"
                        viewBox="0 0 16 16"
                    >
                        <path
                            d="M2 2a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zm4.5 0a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zM8 11a3 3 0 1 0 0-6 3 3 0 0 0 0 6m5 2.755C12.146 12.825 10.623 12 8 12s-4.146.826-5 1.755V14a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1z"
                        />
                    </svg>
                    <router-link
                        class="list-group-item list-group-item-action text-light"
                        to="/coach"
                        >Treneri</router-link
                    >
                </div>

                <div class="d-flex align-items-center">
                    <img
                        src="../images/gym.png"
                        height="25px"
                        width="25px"
                        alt=""
                    />
                    <router-link
                        class="list-group-item list-group-item-action text-light"
                        to="/trainings"
                        >Treninzi</router-link
                    >
                </div>
                <div class="d-flex align-items-center">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="25"
                        height="25"
                        fill="currentColor"
                        class="bi bi-people-fill text-light"
                        viewBox="0 0 16 16"
                    >
                        <path
                            d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6m-5.784 6A2.24 2.24 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.3 6.3 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1zM4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5"
                        />
                    </svg>
                    <router-link
                        class="list-group-item list-group-item-action text-light"
                        to="/members"
                        >Članovi</router-link
                    >
                </div>
            </div>
        </div>
    </div>
</template>

<script></script>

<style scoped>
.modalBody {
    background-color: #282828;
}

.list-group-item {
    background-color: #282828;
    border: 1px solid #282828;
}
</style>
