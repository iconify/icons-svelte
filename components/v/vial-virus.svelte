<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jql1cebqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jql1cebqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:vial-virus" {...props}></Icon>
