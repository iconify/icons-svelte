<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io0x69bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io0x69bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-chart-gantt" {...props}></Icon>
