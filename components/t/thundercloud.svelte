<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw-zrnxal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vw-zrnxal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:thundercloud" {...props}></Icon>
