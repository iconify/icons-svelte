<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n83m5i-4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n83m5i-4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shield-halved" {...props}></Icon>
