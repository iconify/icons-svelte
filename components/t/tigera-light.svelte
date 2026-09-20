<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onssh9hzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="onssh9hzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tigera-light" {...props}></Icon>
