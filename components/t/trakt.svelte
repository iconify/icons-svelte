<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrco7s7xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rrco7s7xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:trakt" {...props}></Icon>
