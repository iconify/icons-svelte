<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnm6697rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnm6697rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shutter-30" {...props}></Icon>
