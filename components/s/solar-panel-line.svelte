<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl6abbbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl6abbbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:solar-panel-line" {...props}></Icon>
