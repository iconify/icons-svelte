<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyo1nlb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dyo1nlb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:tshirt-outline" {...props}></Icon>
