<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuyojqdmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuyojqdmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stopwatch-2-line" {...props}></Icon>
