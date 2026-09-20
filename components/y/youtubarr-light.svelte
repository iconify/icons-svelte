<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2719pbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s2719pbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:youtubarr-light" {...props}></Icon>
