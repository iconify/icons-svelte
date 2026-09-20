<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akkfssfun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="akkfssfun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scholarsome-dark" {...props}></Icon>
