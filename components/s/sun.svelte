<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgx52e-ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fgx52e-ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sun" {...props}></Icon>
