<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoqk-f2dc.css';
import '../../css/q/qrgtcq9tj.css';
import '../../css/x/xu08aye4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoqk-f2dc"/><path class="qrgtcq9tj"/><path class="xu08aye4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-user-bold-duotone" {...props}></Icon>
