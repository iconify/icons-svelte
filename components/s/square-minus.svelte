<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wev7_1bhi.css';
import '../../css/y/yz-efebcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wev7_1bhi"/><path class="yz-efebcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:square-minus" {...props}></Icon>
