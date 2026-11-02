<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1uww3jwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1uww3jwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vip-1-fill" {...props}></Icon>
