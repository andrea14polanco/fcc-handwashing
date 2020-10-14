<script>
    export let progress = 20;
</script>



<style>
    .progress-container{
        margin: 20px 0px;
        border: solid rgb(194,194,194) 3px;
    }
    .progress-bar{
        height: 30px;
        background-color: rgb(77,199,55);
    }
</style>  




<div bp="grid">
    <div bp="offset-5@md 4@md 12@sm" class="progress-container">
        <div class="progress-bar" style="width: {(progress)}%;">
            <span class="sr-olny"></span>
        </div>
    </div>
</div>