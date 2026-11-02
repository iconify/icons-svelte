<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg30chbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg30chbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:send-plane-fill" {...props}></Icon>
