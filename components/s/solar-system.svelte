<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0u_vcc-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r0u_vcc-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:solar-system" {...props}></Icon>
