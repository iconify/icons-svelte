<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blkq5y2_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="blkq5y2_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:writefreely-dark" {...props}></Icon>
