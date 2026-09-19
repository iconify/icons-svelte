<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzih4kbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzih4kbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tilt-window-closed" {...props}></Icon>
