<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjvq1ybgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjvq1ybgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-minus" {...props}></Icon>
