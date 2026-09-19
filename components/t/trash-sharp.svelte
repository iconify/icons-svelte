<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfm5imxge.css';
import '../../css/i/i27ssqklb.css';
import '../../css/c/ce5djubef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rfm5imxge"/><path class="i27ssqklb"/><path class="ce5djubef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:trash-sharp" {...props}></Icon>
