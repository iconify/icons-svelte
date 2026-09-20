<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dygkkyb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dygkkyb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:star-2-line" {...props}></Icon>
