<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0yqracdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0yqracdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-cursor-round" {...props}></Icon>
