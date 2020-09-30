<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        I'm an example component.
                        commit 1
                        commit 2
                    </div>
                    <div id="content">
                        {{ upperContent }}
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                content: 'heheh'
            }
        },
        computed: {
            upperContent() {
                return this.content.toUpperCase()
            }
        }
    }
</script>
