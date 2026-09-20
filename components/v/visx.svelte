<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjb_o1gxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjb_o1gxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:visx" {...props}></Icon>
