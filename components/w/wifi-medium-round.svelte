<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy4-vcchj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy4-vcchj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wifi-medium-round" {...props}></Icon>
