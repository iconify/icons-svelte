<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efumexbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="efumexbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rss-bridge-light" {...props}></Icon>
