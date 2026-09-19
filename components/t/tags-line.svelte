<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lis884bqb.css';
import '../../css/r/rqjikdywo.css';
import '../../css/b/b2d36xbqv.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 lis884bqb"/><circle class="clr-i-outline clr-i-outline-path-2 rqjikdywo"/><path class="b2d36xbqv clr-i-outline clr-i-outline-path-3"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:tags-line" {...props}></Icon>
