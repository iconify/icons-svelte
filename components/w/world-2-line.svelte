<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9u-l8sff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9u-l8sff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:world-2-line" {...props}></Icon>
