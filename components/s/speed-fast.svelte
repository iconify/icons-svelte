<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-3gdxrae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-3gdxrae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:speed-fast" {...props}></Icon>
