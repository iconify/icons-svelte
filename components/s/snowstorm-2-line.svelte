<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7780pv2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7780pv2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowstorm-2-line" {...props}></Icon>
