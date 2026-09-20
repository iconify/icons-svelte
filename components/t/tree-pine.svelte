<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3muaesez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3muaesez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:tree-pine" {...props}></Icon>
