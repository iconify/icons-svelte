<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdx3f7b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fdx3f7b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:times-solid" {...props}></Icon>
