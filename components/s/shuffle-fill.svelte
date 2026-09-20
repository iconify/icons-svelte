<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym-e9bb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym-e9bb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shuffle-fill" {...props}></Icon>
