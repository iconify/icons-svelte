<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wod1mxbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wod1mxbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:stop-circle" {...props}></Icon>
