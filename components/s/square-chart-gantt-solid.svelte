<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4owt0n0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4owt0n0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:square-chart-gantt-solid" {...props}></Icon>
