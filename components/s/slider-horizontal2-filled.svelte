<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke5mo2bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke5mo2bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slider-horizontal2-filled" {...props}></Icon>
