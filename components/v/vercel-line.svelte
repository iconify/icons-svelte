<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dszfdtsvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dszfdtsvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vercel-line" {...props}></Icon>
