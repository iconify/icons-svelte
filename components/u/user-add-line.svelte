<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8d6p67qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8d6p67qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-add-line" {...props}></Icon>
