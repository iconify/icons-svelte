<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2y0w75do.css';
import '../../css/c/cb_h66bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x2y0w75do"/><path class="cb_h66bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wigwam" {...props}></Icon>
