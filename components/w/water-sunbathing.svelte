<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6mr8zbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x6mr8zbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:water-sunbathing" {...props}></Icon>
