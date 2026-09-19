<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-vpgbc_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-vpgbc_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonoff" {...props}></Icon>
