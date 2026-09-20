<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpocgccce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jpocgccce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tree" {...props}></Icon>
