<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8t3-ybky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8t3-ybky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shape-circle-add" {...props}></Icon>
