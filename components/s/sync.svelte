<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgja89bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgja89bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sync" {...props}></Icon>
