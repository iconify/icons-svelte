<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd4vsgtzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jd4vsgtzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:ublock-origin" {...props}></Icon>
