<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bejm4_j3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bejm4_j3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:telephone-accessible" {...props}></Icon>
