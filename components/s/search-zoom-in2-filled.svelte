<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydsm8obkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydsm8obkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-zoom-in2-filled" {...props}></Icon>
