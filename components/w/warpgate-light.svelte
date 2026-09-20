<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec2x_fb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ec2x_fb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:warpgate-light" {...props}></Icon>
