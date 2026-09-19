<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd_dp2bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd_dp2bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:vrt-klara" {...props}></Icon>
