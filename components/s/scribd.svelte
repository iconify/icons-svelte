<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fczfo0zmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fczfo0zmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:scribd" {...props}></Icon>
