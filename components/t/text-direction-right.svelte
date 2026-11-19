<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do7_1qbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do7_1qbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-direction-right" {...props}></Icon>
