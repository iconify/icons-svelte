<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqo7pybtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqo7pybtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:route-off" {...props}></Icon>
