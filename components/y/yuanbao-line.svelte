<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spwm54azc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spwm54azc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:yuanbao-line" {...props}></Icon>
