<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0mjxcc0d.css';
import '../../css/i/icy1kprcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0mjxcc0d"/><path clip-rule="evenodd" class="icy1kprcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tips" {...props}></Icon>
