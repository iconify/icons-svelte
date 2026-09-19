<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drvhp1nhb.css';
import '../../css/e/ew-j63_wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="drvhp1nhb"/><path class="ew-j63_wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:two-factor-authentication" {...props}></Icon>
