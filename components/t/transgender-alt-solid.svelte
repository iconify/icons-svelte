<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjgs9xbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mjgs9xbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:transgender-alt-solid" {...props}></Icon>
