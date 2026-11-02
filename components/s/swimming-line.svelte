<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylhe3bqrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylhe3bqrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:swimming-line" {...props}></Icon>
