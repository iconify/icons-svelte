<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnyf6lycq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lnyf6lycq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shlink" {...props}></Icon>
