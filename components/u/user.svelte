<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssoqd4bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ssoqd4bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:user" {...props}></Icon>
