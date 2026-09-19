<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vth92z2_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vth92z2_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:unlocking" {...props}></Icon>
