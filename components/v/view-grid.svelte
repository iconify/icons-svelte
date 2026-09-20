<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1_7w4pyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1_7w4pyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-grid" {...props}></Icon>
