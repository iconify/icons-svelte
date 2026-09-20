<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtnyc2-wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:wb-twilight-2-sharp" {...props}></Icon>
<style>
:global(.rtnyc2-wv) {
  fill: currentColor;
  d: path("M2.5 19.5v-1h19v1zM6.116 15q.346-2.175 2.008-3.588T12 10t3.876 1.413T17.884 15z");
}

</style>
