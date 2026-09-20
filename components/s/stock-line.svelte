<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfo1lyxxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfo1lyxxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stock-line" {...props}></Icon>
