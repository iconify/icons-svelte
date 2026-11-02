<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slm4kib0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slm4kib0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:walk-line" {...props}></Icon>
