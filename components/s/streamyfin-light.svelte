<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9rsmffna.css';
import '../../css/m/m3cywodxx.css';
import '../../css/v/vvhqz38eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a9rsmffna"/><path class="m3cywodxx"/><path class="vvhqz38eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamyfin-light" {...props}></Icon>
