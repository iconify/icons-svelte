<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4d2hli0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4d2hli0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:toke-square-sharp" {...props}></Icon>
