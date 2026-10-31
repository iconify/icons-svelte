<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkhkkx8gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkhkkx8gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:traffic-light-fill-round" {...props}></Icon>
