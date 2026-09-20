<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1dkykb1h.css';
import '../../css/m/mtoynvb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1dkykb1h"/><path class="mtoynvb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:whatsapp" {...props}></Icon>
