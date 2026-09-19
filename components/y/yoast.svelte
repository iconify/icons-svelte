<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2iqwz2ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="r2iqwz2ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:yoast" {...props}></Icon>
