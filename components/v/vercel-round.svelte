<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frhctlyvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frhctlyvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:vercel-round" {...props}></Icon>
