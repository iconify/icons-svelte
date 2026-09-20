<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqy05tpek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:voice-chat-sharp" {...props}></Icon>
<style>
:global(.yqy05tpek) {
  fill: currentColor;
  d: path("M6.308 10.5h.884v-1h-.884zm2.5 2h.884v-5h-.884zm2.75 2h.884v-9h-.884zm2.75-2h.884v-5h-.884zm2.5-2h.884v-1h-.884zM3 20.077V3h18v14H6.077z");
}

</style>
