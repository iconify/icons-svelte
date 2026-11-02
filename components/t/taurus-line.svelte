<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo-tc_4nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo-tc_4nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:taurus-line" {...props}></Icon>
