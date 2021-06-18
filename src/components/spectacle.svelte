<script>
  export let hour = "";
  export let hourTitle = "";
  export let underTitle = "";
  export let localisation = "";
  export let infos = "";
  export let price = "";
  export let presentation = "";
  export let url = "";
</script>

<article class="spectacle">
  <h4>{hour} - {hourTitle}</h4>
  <p>{underTitle}</p>
  <br />
  <p>{@html presentation}</p>
  <p>
    Lieu: {localisation}
    <br />
    {price}
    <br />
    {infos}
  </p>
  {#if url != ""}
  <div class="player">
    <iframe
      src={url}
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
    />
  </div>
  {:else}
  <span></span>
  {/if}
</article>

<style>
  .spectacle {
    text-align: left;
    border: 3px solid rgb(87%, 87%, 67%);
    background-color: rgba(0, 0, 0, 0.5);
    min-width: 300px;
    padding: 10px;
    border-radius: 5px;
    display: flex;
    flex-direction: column;
    justify-content: space-around;

  }
  .player {
   align-self: flex-end;
   width: 100%;
  }
  iframe {
    width: 100%;
  }
</style>
