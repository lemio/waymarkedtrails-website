<style>
    span :global(button) {
        display: none
    }

    span :global(.map-attribution) {
        position: relative;
        background: none;
        
            color: #101010;
        padding: 0;
    }

    span :global(ul) {
        display: inline-block;
        margin: 0;
        padding: 0
    }

    span :global(li) {
        display: inline;
        list-style: none;
        margin-right: 5px
    }

    @media (min-width: 900px) {
        span :global(a) {
            
        }
    }

    @media (max-width:900px) {
        span {
            position: absolute;
            left: 0;
            z-index: 1;
            background: white;
            color: #101010;
            font-weight: normal;
        }
    }
</style>

<span id="map-attribution"></span>
