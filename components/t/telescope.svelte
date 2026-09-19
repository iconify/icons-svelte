<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4p45cnlu.css';
import '../../css/a/a12tcab1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t4p45cnlu"/><path class="a12tcab1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:telescope" {...props}></Icon>
