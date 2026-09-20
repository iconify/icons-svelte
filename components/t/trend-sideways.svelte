<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc6dvcb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xc6dvcb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:trend-sideways" {...props}></Icon>
