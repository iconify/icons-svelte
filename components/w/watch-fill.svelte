<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1k5gdcrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1k5gdcrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:watch-fill" {...props}></Icon>
