<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3w80_cxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u3w80_cxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:spring" {...props}></Icon>
