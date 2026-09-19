<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwbn2m-gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vwbn2m-gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:sign-hanging" {...props}></Icon>
