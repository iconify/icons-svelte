<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oblu1ib9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oblu1ib9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-2-ai-line" {...props}></Icon>
