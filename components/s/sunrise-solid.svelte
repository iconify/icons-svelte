<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjkogcbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjkogcbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sunrise-solid" {...props}></Icon>
