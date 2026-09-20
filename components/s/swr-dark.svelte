<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xafgut1dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2200,"height":2200};
const content = `<path class="xafgut1dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:swr-dark" {...props}></Icon>
