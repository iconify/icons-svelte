<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blvc0pdsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="blvc0pdsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twitter-light" {...props}></Icon>
