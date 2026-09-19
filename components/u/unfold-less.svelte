<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6diiztnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":384};
const content = `<path class="n6diiztnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:unfold-less" {...props}></Icon>
