<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_yrg8bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_yrg8bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:save" {...props}></Icon>
