<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zat7oigab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zat7oigab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:wifi" {...props}></Icon>
