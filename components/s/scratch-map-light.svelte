<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwhkk5uxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vwhkk5uxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scratch-map-light" {...props}></Icon>
