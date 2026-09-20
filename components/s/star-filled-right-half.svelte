<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf2qh7htv.css';
import '../../css/w/w2alchb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path fill-opacity="0" class="jf2qh7htv"><animate fill="freeze" attributeName="fill-opacity" begin="0.5s" dur="0.5s" values="0;1"/></path><path stroke-dashoffset="36" class="w2alchb6j"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.5s" values="36;0"/></path>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:star-filled-right-half" {...props}></Icon>
