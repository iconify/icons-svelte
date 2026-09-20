<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsoe1tbtj.css';
import '../../css/e/eht21_1kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xsoe1tbtj"/><path class="eht21_1kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:system76" {...props}></Icon>
