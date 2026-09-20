<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp1y_acrv.css';
import '../../css/x/xm9k567sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp1y_acrv"/><path class="xm9k567sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:shx" {...props}></Icon>
