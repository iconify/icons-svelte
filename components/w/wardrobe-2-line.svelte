<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzef7-jsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzef7-jsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wardrobe-2-line" {...props}></Icon>
