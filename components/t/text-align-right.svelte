<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnq6dbbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wnq6dbbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-align-right" {...props}></Icon>
