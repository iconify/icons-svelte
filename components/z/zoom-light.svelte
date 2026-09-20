<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnmnmbbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hnmnmbbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zoom-light" {...props}></Icon>
