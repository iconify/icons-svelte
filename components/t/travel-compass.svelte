<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwj6unb5t.css';
import '../../css/k/kcfkgy84u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rwj6unb5t"/><path clip-rule="evenodd" class="kcfkgy84u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:travel-compass" {...props}></Icon>
