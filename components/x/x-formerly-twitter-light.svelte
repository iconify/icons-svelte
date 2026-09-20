<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2z8qxnta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1227};
const content = `<path class="s2z8qxnta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:x-formerly-twitter-light" {...props}></Icon>
