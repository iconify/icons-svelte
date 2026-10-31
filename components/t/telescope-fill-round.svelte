<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh1w3bcxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh1w3bcxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:telescope-fill-round" {...props}></Icon>
