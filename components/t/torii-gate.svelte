<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2kk3caou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z2kk3caou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:torii-gate" {...props}></Icon>
