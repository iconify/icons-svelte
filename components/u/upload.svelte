<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1rl6abob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1rl6abob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:upload" {...props}></Icon>
