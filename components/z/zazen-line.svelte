<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9zs06bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9zs06bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:zazen-line" {...props}></Icon>
