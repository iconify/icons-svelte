<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px7wvdboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="px7wvdboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:type-h4" {...props}></Icon>
