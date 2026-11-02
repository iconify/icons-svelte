<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5vg2v04s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5vg2v04s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-alert-fill" {...props}></Icon>
