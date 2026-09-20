<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-gphv0ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-gphv0ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:the-lounge-light" {...props}></Icon>
