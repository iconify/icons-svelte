<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4xp6vxxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-pause-outline" {...props}></Icon>
<style>
:global(.w4xp6vxxv) {
  fill: currentColor;
  d: path("M3 21L21 3v10.73h-1V5.422L5.421 20h8.695v1zm13.5 0v-4.884h1V21zm3 0v-4.884h1V21zm-6.786-8.292");
}

</style>
