<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obu_zh1ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obu_zh1ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:style-three-pin-baseball-bold" {...props}></Icon>
