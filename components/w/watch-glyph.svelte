<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u690nsbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u690nsbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:watch-glyph" {...props}></Icon>
