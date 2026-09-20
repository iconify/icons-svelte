<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn0z7abwo.css';
import '../../css/v/vi98df-3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yn0z7abwo"/><path class="vi98df-3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:statamic-light" {...props}></Icon>
