<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj_uz2bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gj_uz2bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ubuntu" {...props}></Icon>
