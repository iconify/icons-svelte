<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kka22lbso.css';
import '../../css/u/u0y1r5zna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kka22lbso"/><path class="u0y1r5zna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-bold-duotone" {...props}></Icon>
