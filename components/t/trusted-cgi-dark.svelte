<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9qpevy0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v9qpevy0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trusted-cgi-dark" {...props}></Icon>
