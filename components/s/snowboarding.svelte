<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy9vtw7wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yy9vtw7wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:snowboarding" {...props}></Icon>
