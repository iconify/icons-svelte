<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voc_w8mff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voc_w8mff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tent-line" {...props}></Icon>
