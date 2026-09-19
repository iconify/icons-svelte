<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie6g9hbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ie6g9hbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:tv" {...props}></Icon>
