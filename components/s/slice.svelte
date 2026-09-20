<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfqd_harf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="cfqd_harf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:slice" {...props}></Icon>
