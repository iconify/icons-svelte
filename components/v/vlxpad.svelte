<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utb9dqwgn.css';
import '../../css/m/mq3padcvo.css';
import '../../css/g/gpfk4wrwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utb9dqwgn"/><path class="mq3padcvo"/><path class="gpfk4wrwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vlxpad" {...props}></Icon>
