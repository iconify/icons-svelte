<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r27vx-biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r27vx-biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:xls" {...props}></Icon>
