<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q59g6fb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q59g6fb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamlink-light" {...props}></Icon>
