<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu-0vpold"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:strk" {...props}></Icon>
<style>
:global(.qu-0vpold) {
  fill: var(--svg-color--277fe3, #277fe3);
  d: path("M12 10.105V3L6.316 13.895H12V21l5.684-10.895z");
}

</style>
