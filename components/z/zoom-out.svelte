<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj2_pbcuj.css';
import '../../css/s/sl3an4zge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="oj2_pbcuj"/><path class="sl3an4zge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:zoom-out" {...props}></Icon>
