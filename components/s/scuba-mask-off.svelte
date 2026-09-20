<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qphgtx_0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qphgtx_0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:scuba-mask-off" {...props}></Icon>
