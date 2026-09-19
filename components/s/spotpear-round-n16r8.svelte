<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0imudn6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0imudn6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:spotpear-round-n16r8" {...props}></Icon>
