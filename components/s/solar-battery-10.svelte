<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_zwxbbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_zwxbbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:solar-battery-10" {...props}></Icon>
