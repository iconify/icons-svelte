<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu-74desw.css';
import '../../css/t/ty2vo4ljz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lu-74desw"/><path class="ty2vo4ljz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:soccer" {...props}></Icon>
