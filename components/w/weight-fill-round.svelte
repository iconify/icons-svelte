<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_36zccwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_36zccwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:weight-fill-round" {...props}></Icon>
