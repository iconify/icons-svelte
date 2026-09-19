<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l66vwzb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l66vwzb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:weebly" {...props}></Icon>
