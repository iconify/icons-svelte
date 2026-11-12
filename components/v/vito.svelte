<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxsy2dbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mxsy2dbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vito" {...props}></Icon>
