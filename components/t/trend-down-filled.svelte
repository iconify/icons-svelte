<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgzsg8svi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgzsg8svi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:trend-down-filled" {...props}></Icon>
