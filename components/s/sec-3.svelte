<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmpycxb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":384};
const content = `<path class="wmpycxb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:sec-3" {...props}></Icon>
