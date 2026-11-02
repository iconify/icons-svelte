<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg_p2w5ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg_p2w5ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spacing-vertical-line" {...props}></Icon>
