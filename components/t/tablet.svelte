<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nja9a3b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nja9a3b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tablet" {...props}></Icon>
