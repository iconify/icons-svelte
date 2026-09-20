<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr7o58bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr7o58bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tv-solid" {...props}></Icon>
