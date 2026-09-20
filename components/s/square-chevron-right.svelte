<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if9nj_b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if9nj_b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-chevron-right" {...props}></Icon>
