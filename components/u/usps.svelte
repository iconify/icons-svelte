<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwdt2v70o.css';
import '../../css/k/kqe51pb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jwdt2v70o"/><path class="kqe51pb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:usps" {...props}></Icon>
