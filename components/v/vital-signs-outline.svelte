<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lavfqbczv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:vital-signs-outline" {...props}></Icon>
<style>
:global(.lavfqbczv) {
  fill: currentColor;
  d: path("M8.15 19.725q-.375-.275-.55-.7L5.3 13H1v-2h5.7L9 17.1l4.6-12.125q.175-.425.55-.7T15 4t.85.275t.55.7L18.7 11H23v2h-5.7L15 6.9l-4.6 12.125q-.175.425-.55.7T9 20t-.85-.275");
}

</style>
