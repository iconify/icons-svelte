<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt70wbcjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xt70wbcjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wifi-above-outstretched-hand" {...props}></Icon>
