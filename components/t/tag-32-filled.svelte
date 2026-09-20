<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nbxykvbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:tag-32-filled" {...props}></Icon>
<style>
:global(.nbxykvbti) {
  fill: currentColor;
  d: path("M15.636 3.952A3.25 3.25 0 0 1 17.934 3h7.818a3.25 3.25 0 0 1 3.25 3.25v7.818a3.25 3.25 0 0 1-.952 2.298l-11.68 11.68a3.25 3.25 0 0 1-4.596 0l-7.818-7.818a3.25 3.25 0 0 1 0-4.596zM23 11a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
