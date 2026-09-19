<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmt5tot6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmt5tot6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:volume" {...props}></Icon>
