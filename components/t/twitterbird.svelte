<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wngk6ibgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wngk6ibgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:twitterbird" {...props}></Icon>
