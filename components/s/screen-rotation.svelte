<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpga2ccyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dpga2ccyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:screen-rotation" {...props}></Icon>
