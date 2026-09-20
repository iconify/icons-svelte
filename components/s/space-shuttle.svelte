<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfdpigeta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hfdpigeta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:space-shuttle" {...props}></Icon>
