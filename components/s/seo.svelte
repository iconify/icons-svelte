<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7_xhfb5l.css';
import '../../css/f/f_1_8rbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="k7_xhfb5l"/><path class="f_1_8rbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:seo" {...props}></Icon>
