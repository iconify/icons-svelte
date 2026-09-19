<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9b1e13eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c9b1e13eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-updated-stroke-12" {...props}></Icon>
