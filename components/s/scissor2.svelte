<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjxdncbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjxdncbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scissor2" {...props}></Icon>
