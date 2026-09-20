<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4jimy5zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l4jimy5zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snikket-light" {...props}></Icon>
