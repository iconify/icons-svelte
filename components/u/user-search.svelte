<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzs1w6bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzs1w6bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-search" {...props}></Icon>
