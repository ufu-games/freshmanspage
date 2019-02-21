<template>
    <section id="freshmansHeader" class="verticalAlignment horizontalAlignment">
        <div class="container freshmansContainer">
            <h1>FRESHMAN'S QUEST</h1>
            <h2>A pixel platformer that takes place at an university/fantasy mixed unverse!</h2>
            <button type="button" class="btn btn-light freshmans-button">
                <p>
                    <i class="fab fa-steam"></i> SOON ON STEAM
                </p>
            </button>
        </div>
    </section>
</template>

<style scoped>
section {
    background: #0ca4a0;
    background: url("../assets/images/1B.png") fixed center;
    color: white;
}

h1, h2, button {
    margin: 10px;
}

h1, h2 {
    text-shadow: -1px -1px 0px rgba(0, 0, 0, 0.25),
                2px 2px 0px rgba(0, 0, 0, 0.25);
}

button {
    padding: .5rem .75rem;
    background: #343a40;
    color: white;
    border: 0px solid black;
}

button:hover {
    background: #343a40;
    color: white;
    box-shadow: -3px -3px 5px rgba(0, 0, 0, 0.25),
                3px 3px 5px rgba(0, 0, 0, 0.25);
}

button p {
    margin: 0;
    display: flex;
    align-items: center;
}

.fa-steam {
    font-size: 2rem;
    margin-right: .5rem;
}

.freshmansContainer {
    padding-top: 15%;
}
</style>