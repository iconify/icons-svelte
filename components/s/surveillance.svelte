<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofa66e5-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ofa66e5-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:surveillance" {...props}></Icon>
