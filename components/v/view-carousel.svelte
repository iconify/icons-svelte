<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugwr-jxmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ugwr-jxmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:view-carousel" {...props}></Icon>
