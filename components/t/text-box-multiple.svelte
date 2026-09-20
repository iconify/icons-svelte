<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4m1t3bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4m1t3bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-box-multiple" {...props}></Icon>
