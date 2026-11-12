<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s68z_rb1l.css';
import '../../css/r/rdd8ibbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s68z_rb1l"/><path class="rdd8ibbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tidyquest-light" {...props}></Icon>
