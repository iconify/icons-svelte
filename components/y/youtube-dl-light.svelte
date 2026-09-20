<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lja0s1wsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lja0s1wsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:youtube-dl-light" {...props}></Icon>
