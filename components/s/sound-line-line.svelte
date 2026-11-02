<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywdt5hb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywdt5hb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sound-line-line" {...props}></Icon>
