<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnetfcc4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mnetfcc4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:summary-kpi-mirror" {...props}></Icon>
