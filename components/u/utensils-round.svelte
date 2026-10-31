<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioannv8yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioannv8yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:utensils-round" {...props}></Icon>
