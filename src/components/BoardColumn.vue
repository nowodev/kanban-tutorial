<template>
    <div>
        <div class="uk-card uk-card-default uk-card-body" id="todo-col">
            <h3>{{ name }}</h3>
            <div class="uk-alert-default" uk-alert>
                <p>Learn Node</p>
                <div class="has-text-centered icons">
                    <button class="uk-button uk-button-primary uk-button-small">
                        Edit
                    </button>
                    <span style="margin:2px">
                    </span>
                    <button class="uk-button uk-button-danger uk-button-small">
                        Delete
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "BoardColumn",
    
    props: ["name"]
}
</script>