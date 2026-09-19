<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm2tfmrxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qm2tfmrxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:venus-mars" {...props}></Icon>
