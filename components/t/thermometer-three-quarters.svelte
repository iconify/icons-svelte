<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppq1nhbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ppq1nhbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:thermometer-three-quarters" {...props}></Icon>
