<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms5fjbcnx.css';
import '../../css/c/c8oz1ac5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ms5fjbcnx"/><path class="c8oz1ac5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamystats-dark" {...props}></Icon>
