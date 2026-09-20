<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol6do99bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol6do99bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-split-horizontal" {...props}></Icon>
