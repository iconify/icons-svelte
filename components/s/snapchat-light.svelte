<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb1elkbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zb1elkbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snapchat-light" {...props}></Icon>
