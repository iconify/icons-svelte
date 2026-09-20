<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-i1fwpqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:summarize-sharp" {...props}></Icon>
<style>
:global(.q-i1fwpqr) {
  fill: currentColor;
  d: path("M7 9h2V7H7zm0 4h2v-2H7zm0 4h2v-2H7zm-4 4V3h13l5 5v13zM15 5v4h4z");
}

</style>
