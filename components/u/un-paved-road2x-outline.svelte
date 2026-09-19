<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yszikpxfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yszikpxfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:un-paved-road2x-outline" {...props}></Icon>
