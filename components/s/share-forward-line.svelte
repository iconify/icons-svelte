<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vin-r_b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vin-r_b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-forward-line" {...props}></Icon>
