<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psvnx_b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="psvnx_b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:vercel-logo" {...props}></Icon>
