<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrdq18bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vrdq18bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:transmute" {...props}></Icon>
