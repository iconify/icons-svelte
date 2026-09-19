<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzkr7cr_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rzkr7cr_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:wifi-signal-off" {...props}></Icon>
