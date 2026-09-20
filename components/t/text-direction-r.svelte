<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwr50vbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwr50vbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:text-direction-r" {...props}></Icon>
