<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8-qwbbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8-qwbbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:windy-rain" {...props}></Icon>
