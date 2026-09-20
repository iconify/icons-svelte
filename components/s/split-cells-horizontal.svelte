<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upsrkxb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upsrkxb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:split-cells-horizontal" {...props}></Icon>
