<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aifktcb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aifktcb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:simpledms-dark" {...props}></Icon>
