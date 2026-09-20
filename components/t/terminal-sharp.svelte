<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3o1gwbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3o1gwbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:terminal-sharp" {...props}></Icon>
