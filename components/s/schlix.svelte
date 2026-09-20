<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3lth67wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n3lth67wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:schlix" {...props}></Icon>
