<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqqvt6lnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hqqvt6lnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:tauri-wordmark" {...props}></Icon>
