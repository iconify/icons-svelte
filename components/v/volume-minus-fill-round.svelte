<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i40lef8wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i40lef8wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-minus-fill-round" {...props}></Icon>
