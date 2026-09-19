<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku-xu3yrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku-xu3yrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:slider-alt-filled" {...props}></Icon>
