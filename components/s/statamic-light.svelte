<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv0lc4yqq.css';
import '../../css/v/vi98df-3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hv0lc4yqq"/><path class="vi98df-3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:statamic-light" {...props}></Icon>
