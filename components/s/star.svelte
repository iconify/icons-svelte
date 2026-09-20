<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_p0ysbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s_p0ysbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:star" {...props}></Icon>
