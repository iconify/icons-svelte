<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryoop_6uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryoop_6uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:surfboard-solid" {...props}></Icon>
