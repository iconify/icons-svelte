<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm3yg-b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm3yg-b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ubuntu-line" {...props}></Icon>
