<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6tj8_big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j6tj8_big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:spacehbit" {...props}></Icon>
