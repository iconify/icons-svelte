<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhhnl_bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hhhnl_bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:text-align-center" {...props}></Icon>
