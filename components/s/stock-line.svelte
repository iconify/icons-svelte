<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ktc704g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ktc704g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stock-line" {...props}></Icon>
