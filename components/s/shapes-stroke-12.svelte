<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dirql1bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dirql1bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shapes-stroke-12" {...props}></Icon>
