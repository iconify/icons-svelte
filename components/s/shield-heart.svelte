<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds2fcdn8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ds2fcdn8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shield-heart" {...props}></Icon>
