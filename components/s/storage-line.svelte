<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1vgprbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1vgprbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:storage-line" {...props}></Icon>
