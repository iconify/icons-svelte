<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8_dy3b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8_dy3b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:univention-corporate-server" {...props}></Icon>
