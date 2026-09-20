<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yavt7lb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yavt7lb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spherical-virus-with-exclamation-point" {...props}></Icon>
