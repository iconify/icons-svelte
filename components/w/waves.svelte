<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zborlrgiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zborlrgiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:waves" {...props}></Icon>
