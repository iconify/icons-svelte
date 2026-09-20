<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgvo1z5ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgvo1z5ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-alert-line" {...props}></Icon>
