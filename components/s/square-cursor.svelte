<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddn_7b-3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddn_7b-3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-cursor" {...props}></Icon>
