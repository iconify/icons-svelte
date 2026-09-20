<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj7-ocbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj7-ocbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wreath-line" {...props}></Icon>
