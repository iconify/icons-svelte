<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s38-92b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s38-92b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:socks" {...props}></Icon>
