<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvoqjmboh.css';
import '../../css/j/jdpi5byld.css';
import '../../css/m/mznjhlbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pvoqjmboh"/><path class="jdpi5byld"/><path class="mznjhlbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:study-skip" {...props}></Icon>
