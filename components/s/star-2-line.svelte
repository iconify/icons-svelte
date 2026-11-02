<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6wth_bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6wth_bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:star-2-line" {...props}></Icon>
