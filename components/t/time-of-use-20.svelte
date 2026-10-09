<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxvrb1ymn.css';
import '../../css/v/vy85ju8br.css';
import '../../css/e/ejsl5db7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sxvrb1ymn"/><path class="vy85ju8br"/><path class="ejsl5db7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:time-of-use-20" {...props}></Icon>
