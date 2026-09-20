<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp13c28wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sp13c28wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-text" {...props}></Icon>
