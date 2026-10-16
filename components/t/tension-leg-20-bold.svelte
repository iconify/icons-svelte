<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucme140zl.css';
import '../../css/m/mi8bjn4ds.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ucme140zl"/><path class="mi8bjn4ds"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tension-leg-20-bold" {...props}></Icon>
