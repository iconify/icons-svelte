<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usefx23gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usefx23gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wind-fill" {...props}></Icon>
