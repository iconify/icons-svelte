<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woxf2db7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="woxf2db7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:rss-square" {...props}></Icon>
