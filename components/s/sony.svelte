<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaudqfbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zaudqfbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sony" {...props}></Icon>
