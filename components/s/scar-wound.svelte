<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2gcj_bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d2gcj_bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scar-wound" {...props}></Icon>
