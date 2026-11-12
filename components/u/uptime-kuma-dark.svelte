<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j14wnj9wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j14wnj9wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptime-kuma-dark" {...props}></Icon>
