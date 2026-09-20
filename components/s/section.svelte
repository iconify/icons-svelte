<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfq8itbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfq8itbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:section" {...props}></Icon>
