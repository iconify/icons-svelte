<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmu9ifn_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmu9ifn_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:subway-wifi-line" {...props}></Icon>
