<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmiy_hrng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xmiy_hrng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thrust-bend" {...props}></Icon>
