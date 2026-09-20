<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6tui-2gp.css';
import '../../css/w/wyvbzqpgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6tui-2gp"/><path class="wyvbzqpgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:time-clock-nine-twenty-five-1" {...props}></Icon>
