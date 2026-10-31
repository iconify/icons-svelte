<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw2f2mrxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw2f2mrxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-terminal-gloss" {...props}></Icon>
