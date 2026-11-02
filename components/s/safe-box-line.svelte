<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulin1z6mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulin1z6mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-box-line" {...props}></Icon>
