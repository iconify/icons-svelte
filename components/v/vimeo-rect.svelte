<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooipf_b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ooipf_b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:vimeo-rect" {...props}></Icon>
