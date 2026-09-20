<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv0x06bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zv0x06bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sass" {...props}></Icon>
