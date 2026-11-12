<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-1lhac_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-1lhac_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:smart-camera" {...props}></Icon>
