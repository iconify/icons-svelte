<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc46r_4jg.css';
import '../../css/r/r0a92247z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oc46r_4jg"/><path class="r0a92247z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:scrubber" {...props}></Icon>
