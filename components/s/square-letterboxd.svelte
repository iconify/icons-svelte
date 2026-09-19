<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5b61ccaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="b5b61ccaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-letterboxd" {...props}></Icon>
