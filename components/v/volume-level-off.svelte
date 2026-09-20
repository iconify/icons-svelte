<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rblvwmbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rblvwmbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:volume-level-off" {...props}></Icon>
