<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouy_cybgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="ouy_cybgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:smartphone-setting" {...props}></Icon>
