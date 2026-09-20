<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbyi8zb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbyi8zb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:voelkner" {...props}></Icon>
