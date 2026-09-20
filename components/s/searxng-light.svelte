<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/horo-b3sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="horo-b3sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:searxng-light" {...props}></Icon>
