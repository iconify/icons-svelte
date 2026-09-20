<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8az3ib2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8az3ib2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:six" {...props}></Icon>
