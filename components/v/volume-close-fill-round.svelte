<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omt5egbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omt5egbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-close-fill-round" {...props}></Icon>
