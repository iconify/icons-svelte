<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szaj81gsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="szaj81gsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:satellite-light" {...props}></Icon>
