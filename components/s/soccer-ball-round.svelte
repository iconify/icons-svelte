<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyt1u30bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyt1u30bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:soccer-ball-round" {...props}></Icon>
