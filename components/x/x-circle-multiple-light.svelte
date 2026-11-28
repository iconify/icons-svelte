<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9vx3fbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="h9vx3fbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:x-circle-multiple-light" {...props}></Icon>
