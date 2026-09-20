<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0v1_wsnp.css';
import '../../css/d/dq4s8_baf.css';
import '../../css/z/zqx0zmbos.css';
import '../../css/y/ychnm4ptg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0v1_wsnp"/><path class="dq4s8_baf"/><path class="zqx0zmbos"/><path class="ychnm4ptg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sharry-dark" {...props}></Icon>
